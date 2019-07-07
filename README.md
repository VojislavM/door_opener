# door_opener
Story about hacking illegally closed door

I want to share with you one of my stories. This is something that is currently making my life a bit harder so I wanted to turn it around and have a little fun. Although this will be in a blog post format I think the GitHub is the right place to publish it because it will also be a kind of user guide how to stop bullies with technologies, or et least the one I am having trouble with, which in my opinion is awesome.

## introduction
I am currently living in Novi Sad, Serbia in one smaller building. There are 12 flat and 2 shop units and the whole first floor and street shop is owned by the family who had a house in the same place where the building is now. Not to bore you with the details, and to make this story short, they had a misunderstanding with the investor who built the building and they are on the court. This is fine with me, but (of course, there is a but...) that family still think they own the lend benight the building. This is the reason why they locked the entrance to the building parking, and they are telling us to pay them for it. Because we have realy inefficient police, courts, country, etc. they get away with this. Now they have istalled the motoriezed gate, which opens with radio remote. 

## gole
Mess with the gate and see what heppends. :)

## plan
### gate

Gate is pretty standard, but unfortunately, I did not see any company logo on it. Never the less most of the gates use some standard frequencies for opening them with small remotes. These remotes usually do not have some fancy safety features like frequency hopping and they are just sending the modulated bitstream into the air. If the gate receiver received the correct signal it opens the gate. Simple as that. 

### plan 
Because this gate is used just a few times a day, I will need to record and catch that signal. To do that I can use and SDR device like [RTL 820T2 SDR Dongle](http://www.hamgoodies.co.uk/rtl-sdr-dongle) and RaspberryPi as an SDR server and collect all the data. 

