# About BEEM #
## What does BEEM mean? ##

BEEM means "Boost your Eyes, Ears and Mouth"

## Do you guys have a XMPP groupchat room? ##

Yes. You can find us at **beem@conference.elyzion.net**. You can also find us on the **IRC** at the channel **#beem** on **freenode** network.

## Why BEEM needs those crazy permissions?? ##

Here is a list of the different permissions used by BEEM
Permission 	Need
android.permission.INTERNET 	to access the internet connection
android.permission.VIBRATE 	to set vibrate on Beemç notifications
android.permission.WRITE\_EXTERNAL\_STORAGE 	to stock the avatar datas on the SDCARD
android.permission.ACCESS\_NETWORK\_STATE 	to check the connectivity status
com.beem.project.beem.BEEM\_SERVICE 	Custom permission which will be used to allow other applications to use the Beem service

## Can I use BEEM in my own project? ##

You can use the source code of beem (in free or paid apps http://www.gnu.org/philosophy/selling.html ) as most as you want as long as you respect the requirements of the gplv3 : http://www.gnu.org/licenses/gpl.html.
We have no commercial business around BEEM but we will really glad if other people can bring back to the upstream their ameliorations.
If you have any question we will be glad to help you.


## I want to help, what do you have for me? ##

Lots of stuff to do. Just see all those crazy tasks.
But I'm not a programmer!

That's OK. If you are into drawing stuff, you could design an icon set, emoticons set, or such. If you know some languages, you could help with translations. In either case, please just use BEEM, report your ideas, suggestions, tell us about your experience and feelings.

And, of course, help us to build a community, stay around in our XMPP conference, beem@conference.elyzion.net , chat around, answer newbies' questions and such. You can't imagine how it helps when there is at least a person or two that can help you with all that support-related stuff so that you can free a bit of time and context switches to write a bit more code.

# Common issues #

## I use a Google Apps account and I can't connect with BEEM !!! ##

The Gtalk server use a non standard authentication scheme : they don't use the user part of the jid to authenticate but instead they use the full jid.
Starting to Beem-0.1.5 version, you can use an option in the advanced preferences to use the full jid to authenticate.
For previous version, if the domain part of your JID is not gmail.com or googlemail.com you have to enter in BEEM a jid in this form : user@example.com@example.com