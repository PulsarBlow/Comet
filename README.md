# Comet

### A ready-to-use MeteorJS project layout for fast prototyping

```Version 1.0-alpha```

##### What is it ?

Ok, you just got an awesome idea and want to prototype it ASAP.  
Supposedly you decided to use [Meteor](http://www.meteor.com) (because it is the best reactive JS framework around, isn't it?).  
Clone Comet and you're ready to go.



##### How to install ?

First, you need a working Meteor environment. Preferably a >=0.8.0 one, with Meteorite installed.  
Meteorite is required to fetch out meteor packages via [Atmosphere](https://atmospherejs.com).

```npm install -g meteorite```

Then, create your Meteor app :

```meteor create myapp```

As we can't directly git clone into an existing directory, we need to do a 2 steps physical merge.

Clone Comet in a temp folder :

```git clone https://github.com/PulsarBlow/Comet temp```

Physical merge the temp folder into your meteor app folder :

```mv temp/* myapp```

Launch your meteor app with mrt

```mrt -p 3000```

... and you can start coding.


Includes :

* Meteor 0.8.0
* HTML5 BoilerPlate v4.3.0 (Fitted custom build!)
* Bootflat 2.0

##### Working on Windows ? Get started in seconds...

If you are developing on Windows, you can get a complete online meteor dev box, up to date, for free.

Head up to [Nitrous.io](https://www.nitrous.io/join/Nx2ZUMqxfNI?utm_source=nitrous.io&utm_medium=copypaste&utm_campaign=referral).

They provide an online neat IDE with some preconfigurated Meteor boxes and a sync tool if you rather like to code localy with your prefered IDE.  
Get started coding your prototype in seconds.  
