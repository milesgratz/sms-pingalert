# sms-pingalert
Simple bash script to notify via SMS when a server goes offline

# Installation Instructions
1. Adjust variables for your environment

2. Set <b>sms-pingalert</b> as executable
        
        chmod +x sms-pingalert

3. Adjust crontab to run on reboot

        crontab -e
        @reboot bash /opt/sms-pingalert >/var/log/sms-pingalert.log
