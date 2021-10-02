## WindowsRDP

Create a free VPS with 2cpu-7gb Ram FREE with Github:

+ Click Fork in the right corner of the screen to save it to your Github.
+ Visit https://dashboard.ngrok.com to get NGROK_AUTH_TOKEN
+ In Github go to Settings> Secrets> New repository secret
+ In Name: enter NGROK_AUTH_TOKEN
+ In Value: visit https://dashboard.ngrok.com/auth/your-authtoken Copy and Paste Your Authtoken into
+ Press Add secret
+ Go to Action> CI> Run workflow
+ Reload the page and press CI> build
+ Press the down arrow on Connect To Your RPD to get IP, User, Password.

## Useful Info

* Runners can run sessions for up to 6 hours. So you have about 6 hours minus the minute setup time to poke around in these runners.
* If using for introspection, add the [`continue-on-error`](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/workflow-syntax-for-github-actions) property to the failing step before these remote connection steps.


## ALL RIGHTS RESERVED / TUTTI I DIRITTI RISERVATI
* THIS IS ONLY FOR EDUCATIONAL PURPOSES
* DO NOT SHARE THIS WITH ANYONE
* NON CONDIVIDERE QUESTO CON NESSUNO
* DON'T USE FOR MINING OR ILLEGAL USE
