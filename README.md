# YunoHost Huginn app #

##Notes

- Work only on root-domain
- No SSO auto login
- Eveything is compiled from source, may take a while to install.

##Tested on :

 - Debian 7.9 inside Docker

##Config Post Install

Change the Unicorn config if needed, the [requirements.md](https://github.com/cantino/huginn/blob/master/doc/manual/requirements.md#unicorn-workers) has a section explaining the suggested amount of unicorn workers:

    # Increase the amount of workers if you expect to have a high load instance.
    # 2 are enough for most use cases, if the server has less then 2GB of RAM
    # decrease the worker amount to 1
    sudo -u huginn -H editor config/unicorn.rb

##Files
`unicorn.rb` and `.env` are located in :

    /home/hugin/hugin

**Note:** You have to re-export the init script every time you change the configuration in `.env` or your `Procfile`!

    sudo rake production:export


#More information:    
https://github.com/cantino/huginn
