# SOS
INFO 448 Final Project 

Timer App was created using Reso Coder tutorial on Youtube. Uses the Dreaming Code Library.
Google Map fragment was created using boilerplate code from the SDK and tutorials. 

Project Proposal
INFO 448, Fall 2018
Created by

JuanAcevedo
Yichao Wang
Sarthak Turkhia
Zubair Amjad

As of iOS 11, Apple introduced an emergency SOS feature that is available to use on
their mobile devices. This feature can be used on any mobile device that supports iOS 11 and
up. The purpose of the emergency SOS feature is so that if the user gets into any sort of trouble
or emergency, they can quickly pick up their phone, activate the feature using some button
combination, which then contacts emergency services and alerts a set of designated contacts
that informing them that they are in trouble.
This emergency SOS feature has been adopted by some Android manufacturers, one of
them being Samsung. However, with the fragmentation of Android's ecosystem and some
manufacturer’s lack of system updates, this feature is only available on select recent devices
with the latest firmware updates. Our goal for this project is to build an app that works in a
similar way to iOS’ SOS application but built it in a way, such that a person can download and
run our app on any android device, instead of having to rely on the manufacturer to implement
this feature or obtaining a phone that already has this feature.
Our app will be targeted towards mobile devices, specifically smartphones because it will
make use of mobile capabilities such as data/telephony services to make phone calls and send
SMS messages, GPS service to get the user’s location. These are functions that are going to be
present on most smartphones but may not necessarily be present on tablets, media players,
and such. This is the same reason we are not building this application as a desktop
app/website because it makes specific use of a phone’s capabilities. If we had the same
functionality such as accessing precise location and making/receiving phone calls, SMS, we
would be able to build it for those platforms too. In addition, most users carry smartphones with
them more often than they carry their tablets, laptops etc.
With this idea of supporting as many Android devices as possible, we will be targeting a
lower SDK version to ensure app compatibility with a large percentage of Android phones being
used today. Our Emergency SOS app will be built in a way that is easy to use and navigate so
that users can easily start our app and use the emergency features quickly, and without any
struggle. This is important because, in a real emergency, the user might be in a frantic rush to
pull their phone out or might be too stressed/scared to perform otherwise simple tasks. Making
our app as simple and intuitive as possible whilst navigating will help mitigate these issues.
Furthermore, allowing the user to contact emergency services in addition to alerting
their designated contacts will add another layer of emergency assistance because in many
cases the police might be able to respond faster than any designated contacts. When it comes
to emergencies, reducing the response time can be a matter of life and death.
Our application will also implement a check-in feature so that if users think that they
might be in trouble later, they can check in with our app periodically by pressing a button. If they
fail to check in our app will alert them they didn’t check in, and if enough time expires after that,
our app will automatically call emergency services, and the user’s emergency contacts will be
notified with the last location.
We will also be implementing a map feature so that when the user chooses to go to the
map section, they can see all nearby emergency service locations such as hospitals, police
stations, and pharmacies.
Lastly, we will be implementing an audio feature, so that users can make an audio
recording if they want to leave their phone on and record some type of audio.Threats are not
always necessarily imminent and they can often be looming over a longer period making the
victim feel unsafe and unportected. In these cases the user might feel safer knowing that they
have recoridings of the events from thier life stashed away on a drive somwehere that can be
accessed my family or close friends if need be. Or perhaps there might be a situation where the
user needs to record something being said to them in an emergency and they need to keep
track of it for a later references even if their phone gets lost or loses all its data. So what we
want to do is setup a feature that automatically backs up the files to the cloud, specifically
google drive. This way they can always have a copy of the file in case it is deleted from their
device, they can even share it with people they trust in case of an event where the user cannot
be located. Users will be able to make multiple audio recordings, which they can then listen to at
any point in time. This will make use of the devices microphone to record the user.
User Stories 

● As a user, I want to be able to make an emergency call to emergency services easily
and quickly in urgent cases

● As a user, I want to be able to send my location and a short message to my designated
contacts in case there is an emergency

● As a user, I want to be able to pick between calling emergency services or a predefined
contact in case there is an emergency

● As a user, I want to be able to set a timer so that if the timer expires, emergency
services/emergency contacts will be contacted

● As a user, I want to be able to check in to my app, to set a status that I am currently
safe, and if I don’t check in at a given time, emergency services/contacts will be
called/messaged.

● As a user, I want to be able to see my current location and nearby emergency service
centers.

● As a user, I want to be able to set a recorder to record audio in case something happens
to me.

● As a user, I want to be able to access my audio recordings, and I want them to be saved
on my phone for later, or on the cloud in case they are deleted.
There are four main screens for the app. The menu/setting screen allows the user to add
emergency contacts. The map screen displays a map and allows the user to get their current
location and also be able to send it. The emergency screen allows a user to text and call the
emergency contacts. The check-in screen allows user to set a timer and set the status to
indicate if user is currently safe. The
Prototype
https://www.figma.com/file/KS1zCJZa7R23Nn8fS8HHkqNe/Introduction?node-id=0%3A1
