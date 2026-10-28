<!-- Source: Cockpit Control Forces.pdf, pages 1–7 -->

### Cockpit Control Forces Or How Robust Do Driver Controls Really Need To Be?

By Steven Fox Originally published: July, 2010

I look forward to FSAE/FS competitions, not only for the obvious reasons (you get to see a lot of neat, different cars, and talk to a lot of incredibly bright engineering students), but also because it is the one time of year when all the Design Judges, Tech Inspectors, Rules Committee members, and the other visionary individuals who make FSAE/FS what it is, are gathered together. We use this opportunity to talk over ideas face to face and gain a better view of the ‘Big Picture’ so to speak. One of the topics that came up over dinner one evening, this past May, was sub-system robustness, or how strong does a steering/brake/accelerator/gearshift (you pick one) system really need to be?

This is a topic which all FSAE/FS volunteers (Design Judges & Scrutineers in particular) are sensitive to because we, on occasion, have actually broken student built cars. Make no mistake about it, when this happens, we feel very badly that we have broken something which students have put long hard hours of design/build/test time into. However, we are also quick to point out that we would much rather see the suspect part break standing still, rather than out on the track where someone (be it a student driver, or worse yet, an innocent spectator) could be injured or worse. Unfortunately, some students get upset, and feel that they are being unfairly singled out, because: “We tested that \_\_\_\_ (insert one: brake pedal, steering shaft, accelerator pedal, gear shift, etc) beyond reasonable limits, and it didn’t break for us.”

This article will look at each of the different sub-systems that a driver exerts force to operate and help you determine what the reasonable forces for normal operation are. It is not my intention to tell you how to design your car. This is just one example of how to go about designing a reasonably robust car. This article will (hopefully) help you identify what level of force your car should be able to withstand without driver-induced damage. When determining how strong any sub-system really needs to be, a common saying we use in motorsports is: “Never underestimate the strength of a scared driver!”

Steering System

There are two types of steering forces we will discuss. The first will be steering wheel torque, or how much force can a driver put into the steering system through ‘normal’ actuation of the steering wheel. The second steering system force we will talk about is lateral (radial) force, or how much can a driver pull up, down, or sideways on the steering wheel and column. We will not discuss axial force imparted

![Figure on page 1](assets/Cockpit%20Control%20Forces/figure_001_p1.png)

during the dynamics of a collision. Axial analysis is beyond the scope of this article.

First, let us look at the most common types of steering system failures in FSAE/FS cars. A recurring problem we see is a lack of proper steering column support. When a steering wheel can be firmly pulled up, down or sideways, and the Design Judge or Scrutineer can detect noticeable compliance, you definitely have a problem.

This is usually due to the fact that the steering column only has one support, and the support (usually a metal sleeve) does not support the shaft over a sufficient length. A better design would have two supports per shaft. The farther apart the supports are, the less compliance there will be in the finished assembly. We also see all types of bearings/sleeves supporting the shaft, ranging from very well engineered radial ball bearings, to all types of bushings, made from all types of materials, to nothing more than a metal sleeve substantially bigger than the steering shaft (with all of the excess compliance that comes with that sloppy design!).

![Figure on page 2](assets/Cockpit%20Control%20Forces/figure_002_p2.png)

We also see all types of steering shaft couplers and u-joints which are under-designed, worn out, improperly installed or simply should never be used in a steering system in the first place. The most common type of coupler failure we see is the notorious shaft in a metal sleeve with a cross drilled hole with a pin/bolt through it. Typically the shaft is not hardened, the hole is too big, or the holes don’t line up properly. This results in a sacrifice of adequate cross sectional area, which causes a shearing failure, or at the very least, lots of extra compliance.

Another common failure we see is adhesive failure of a shaft and coupler which has been bonded together with some sort of ‘super dooper epoxy’. Your steering system is no place for bonded joints. The better way to couple any of your steering components together is with splined joints.

I am not recommending this, but this was Pat Clarke’s (Chief Design Judge, FSG) karting solution (back in the ‘70s, when he raced). If the kart had a tubular column (most do) Pat turned up a 5 cm (2”) long aluminum plug for the top of the shaft.

![Figure on page 2](assets/Cockpit%20Control%20Forces/figure_003_p2.png)

Steering System Torque / Force

So, how much torque / force does your steering system normally require to operate, and how much torque / force should it reasonably be able to withstand?

Normal steering operating torque / forces depend on a number of variables. You can build a 135 kg (300 lb) car with very narrow, high pressure tires, at zero scrub radius, with zero KPI, and zero caster, lots of steering ratio, and the steering force required will be very small indeed, maybe as small as 1.3-2.7 Nm (1-2 ft.lb.). This car would be worthless to try and drive competitively as it would have a ‘dead’ feel, and give the driver no feedback to his steering inputs. The opposite extreme would be a very heavy car with wide, low pressure tires, lots of scrub radius, lots of KPI, caster, and a low steering ratio. You better start working out now if you are going to drive ‘that’ car for any distance… The best suspension/steering geometry for the tires you have chosen, for use in a lightweight FSAE/FS car, will result in reasonable steering forces, which a driver can maintain for at least an hour of non-stop, racing velocity driving. Typically we see the above average FSAE/FS cars at somewhere around 4-11 Nm (3-8 ft. lb.) of steering effort needed at a standstill. Of course, that torque force will drop as the car starts rolling. A note in passing: One of the tests we sometimes conduct during engineering design judging is to lift the front of the car off the ground, and check for steering wheel effort. The best cars will be able to twirl the steering wheel from lock to lock with one little finger…

One of the FSAE - Michigan Design Judges (Steve Lyman aka ‘Ergo Man’) was kind enough to send along the following data. This is static measured torque data he has acquired over the years using a Sensor Development hand wheel torque sensor:

Autokraft Midget = 6.0 Nm (55 in-lbs) No power steering, 380mm (15.0”) Ø steering wheel. Lola T332 = 5.5-8.5 Nm (50-75 in-lbs) No power steering, 318mm (12.5") Ø steering wheel. Dodge Viper SRT-10 = 4.5 Nm (40 in-lbs) Power steering, 350mm (13.7" Ø steering wheel. Lotus 20 = 4.0-4.5 Nm (35-40 in-lbs) No power steering, 330mm (13.0") Ø steering wheel. Lola T190 = 6.0-7.5 Nm (55-65 in-lbs) No power steering, 318mm (12.5") Ø steering wheel.

Production cars from the automotive OEMs have steering torque specifications of 175 Nm (130 ft.lb) yield with 240 Nm (175 ft.lb.) minimum ultimate strength. Rest easy, we will NOT be testing or requiring you to achieve these levels of robustness on your FSAE/FS car. These are specifications set by car manufacturers designed for dealing with unusual customer use, and as protection from liability lawsuits.

In discussing these types of steering torque loads with formula race car designers & builders from around the world we are all in clear agreement that your FSAE/FS car should never have the steering wheel, shaft, rack, or linkages break… no matter how much force your driver puts into it.

For the purposes of this article, we decided to determine what maximum steering torque limits are reasonable. We instrumented a FSAE car with a 254mm (10”) diameter steering wheel, in order to assess how much peak torque a driver could transmit to the steering column while seated in the car. This force varies depending on how far the steering wheel is away from the driver’s chest. We tested with arms fully extended (Extended), arms at mid reach (Mid), and then with the wheel held close to the chest (Close). The closer to the chest, the greater the torque the drivers could generate. See the chart below for peak steering torque forces generated.

|  |  |  |  | Extended | Mid | Close | ∆ Delta |
|---|---|---|---|---|---|---|---|
| Driver | Sex | Height | Weight | Nm (ft.lbs.) | Nm (ft.lbs.) | Nm (ft.lbs.) | Nm (ft.lbs.) |
| MAT | F | 183cm (66") | 64kg (140 lbs) | 34 (25) | 41 (30) | 41 (30) | 7 (5) |
| CMM | F | 173cm (68") | 77kg (170 lbs) | 34 (25) | 37 (27) | 43 (32) | 9 (7) |
| BAK | M | 170cm (67") | 70kg (155 lbs) | 47 (35) | 41 (30) | 47 (35) | 0 (0) |
| SAK | M | 188cm (74") | 64kg (140 lbs) | 41 (30) | 47 (35) | 47 (35) | 7 (5) |
| NJP | M | 170cm (67") | 59kg (130 lbs) | 41 (30) | 47 (35) | 47 (35) | 7 (5) |
| MAF | M | 175cm (69") | 77kg (170 lbs) | 50 (37) | 61 (45) | 56 (41) | 5 (4) |
| DHC | M | 180cm (71") | 73kg (160 lbs) | 47 (35) | 68 (50) | 61 (45) | 14 (10) |
| SKW | M | 175cm (69") | 68kg (150 lbs) | 47 (35) | 61 (45) | 61 (45) | 14 (10) |
| JAC | M | 175cm (69") | 64kg (140 lbs) | 54 (40) | 61 (45) | 61 (45) | 7 (5) |
| TMJ | M | 190cm (75") | 70kg (155 lbs) | 50 (37) | 57 (42) | 61 (45) | 11 (8) |
| YAY | M | 175cm (69") | 68kg (150 lbs) | 54 (40) | 61 (45) | 68 (50) | 14 (10) |
| AAS | M | 183cm (72") | 73kg (160 lbs) | 68 (50) | 68 (50) | 68 (50) | 0 (0) |
| JWW | M | 175cm (69") | 64kg (140 lbs) | 50 (37) | 64 (47) | 70 (52) | 20 (15) |
| SMF | M | 183cm (72") | 84kg (185 lbs) | 71 (52) | 81 (60) | 81 (60) | 11 (8) |
| JAS | M | 175cm (69") | 66kg (145 lbs) | 50 (37) | 74 (55) | 84 (62) | 34 (25) |
| PKF | M | 175cm (69") | 100kg (220 lb) | 66 (49) | 80 (59) | 88 (65) | 22 (16) |

All test subjects with the exception of one (the author) were average college engineering students between the ages of 19 and 23. No ‘body builder’ types volunteered for the test.

Most FSAE/FS cars have the steering wheel positioned 300mm to 450mm (12” to 18”) away from the driver’s chest (mid span of your total forward reach). It is reasonable to conclude that any well constructed FSAE/FS car should be able to withstand a minimum of 100-135 Nm (75-100 ft.lb.) of torque / force applied at the steering wheel with no steering system failure.

We often also see silly undersized wheels, similar to Nintendo PlayStation, and other PC game controllers. You NEVER see a ‘real’ race car with such a tiny wheel and there are good reasons for

![Figure on page 4](assets/Cockpit%20Control%20Forces/figure_004_p4.png)

this.

A second issue is the use of carbon fiber for steering wheels. Is it appropriate without an armature of aluminum? How is the steering torque reacted into the wheel assembly? What about the potential fracture of the wheel in an accident, leaving razor sharp edges to hurt the drivers hands? All of these are negative points, which should eliminate them from consideration.

Steering System Lateral (Radial) Forces

Steering system lateral (radial) forces are relatively small when the car is on the track, running at speed. However, that does not relieve you of the responsibility to mount your steering wheel & column in a workmanship like fashion. Any steering wheel / column should be able to withstand at least a 660 N (150 lb.) lateral (radial) force without failing.

Braking System

What pedal force should you be designing for under normal on-track conditions? This number varies according to driver preference. Some drivers like a pedal force as low as 110 N (25 lb) force per G of stopping force. That would result in a fairly sensitive brake system, which will be difficult to precisely control. Other drivers might prefer a brake pedal effort of 440 N (100 lb) force per G of stopping force (or higher). A brake system with a pedal effort that high might be difficult to modulate, and might not give the driver the ultimate control over the car that he (she) would like.

A note in passing: Some engineers specify pedal force at wheel lock-up, as opposed to pedal effort per G force. During Design judging either answer is acceptable. Just be clear in how you have specified your brake system, when discussing it with a Design judge. Pedal geometry is also important. When the pedal goes ‘over center’ the rate falls and the feedback to the driver is confusing. Bu that is a subject for another article.

We see FSAE/FS brake pedals and brake pedal mounts fail all too often. Here is my statement: Your brake system should be so robust, that the driver cannot break it by pushing on the pedal… with any amount of force he (she) can generate. As Mike O’Neil (Chief Design Judge, FSAE-CA ret.) is fond of saying: “When everything else on the car has failed, the brakes should be the last thing still working.” Mike also quickly pointed out that any brake pedal mount he has ever designed and built was so strong that the master cylinder pushrods would buckle before the pedal broke!

An average adult male can leg press 225-270 Kg (500-600 lbs). For this article, let’s use the upper number, which means that one leg can exert 1330 N (300 lb) force on the brake pedal, under normal circumstances. Add a 10% safety factor and I will respectfully suggest that your brake system should be able to withstand a 1470 N (330lb) force with NO damage to your brakes. The official FSAE rules require that your brake pedal be designed to withstand a force of 2,000 N (450 lb). One too many broken brake pedals brought about that rule a few years ago…

You also have to react that force. A failed seat mount can cause ‘brake failure’ and seat compliance (even a foam insert) may limit the amount of pressure that can be applied. Similarly, compliance in the pedal box/mounting can limit ultimate pressure. Something that worries me a little is the ‘adjustable’ pedal boxes we see. Some are made to fail under high load. Another potential problem is that the driver may ‘pull’ on the steering wheel as he applies high brake pressure (See earlier comments on carbon steering wheels).

In talking to a lot of different professional (race) car builders we are all in agreement that 1470 N (330 lbs.) force is the absolute bottom end of the brake force threshold you should be designing and building to. Anything you build should be robust enough to take at least that amount of force. Remember: Never underestimate the strength of a scared driver.

Accelerator System

Your accelerator pedal should require a relatively light effort. (Neil Roberts’ book: Think Fast, The Racer’s Why-To Guide To Winning, covers throttle linkage ratios quite nicely. I recommend reading it.) Because the accelerator only requires a fraction of the force needed for a brake pedal, it does not have to be constructed as robustly as a brake pedal. The driver can still generate well over a thousand newtons (several hundred pounds) force, so the accelerator pedal needs to have an over-travel stop, capable of withstanding this high level of force.

NOTE: The throttle cable should NEVER be used as the pedal stop! The Design Judges (and Scrutineers) always like to see a good push-pull cable used instead of a pull only cable. This can sometimes ‘save your bacon’ if you experience a stuck throttle, by allowing you to pull the throttle closed with a toe under the pedal…

Gear shift System

Stand-alone, mechanical, shift levers have to be designed strong enough for the force needed to effect the shift. Sounds like a plainly obvious statement, doesn’t it? Yet every year we see all types of shift levers under-designed, poorly manufactured, or with so much compliance that they are not very driver friendly. The ratio of the lever has everything to do with how much force is required from the driver. We often see lever ratios that are not well thought out, requiring too much effort from the driver. This not only means that the lever has to be built stronger (heavier), but also means that the higher force required will fatigue your driver sooner.

Manually operated clutch mechanisms mounted on the steering column bring their own unique set of problems. The reaction force on the lever is through the steering wheel and again we have to ask how that force is reacted through the wheel and into the steering column and supports.

Adrenalin, the great equalizer!

I have not yet mentioned this little power adder called adrenaline. Adrenalin to us is like nitrous oxide is to an engine. You get an increased power output for a short period of time. When a driver is scared it is normal to experience an increased adrenalin level. Adrenalin gives the driver the ability to far outperform any previously recorded peak strength levels. The excitement of the moment during ‘the heat of the battle’ also results in increased adrenalin. When the driver moves the controls faster, in an attempt to get a lower lap time, he (she) exerts more force on all cockpit controls. As a result, all of your cockpit control devices need a little extra safety margin just for the adrenalin / excited driver effect.

Summary

Minimum driver applied forces, you should be designing/building/testing for:

- Brake System – The brake system must be able to withstand at least 2,000 N (450 lb) force
    without damage. This is per FSAE Rules.
- Steering System Lateral Force – The steering wheel and steering column should be able to withstand at least 660 N (150 lb) lateral (radial) force before failure.
- Steering System Torque – The steering system should be able to withstand a minimum of 100 Nm (75 ft lb) force, applied at the steering wheel, before failure.

With a basic understanding of driver strength and a little attention to detail, you will be able to design a racecar (err, student built vehicle, as the insurance companies want us to call them) which is not only fast, but also strong and reliable. Remember, that safety is always your first priority when designing anything. If you wouldn’t get in the car yourself, then don’t jeopardize your driver’s life either. Your objective is not to scare your driver as if he (she) was on an amusement park ride, but rather to make the car supremely comfortable and easy to control which increases your driver’s confidence level and helps him (her) excel on track!

Until we meet again at a competition, or a college campus near you, please remember to have fun, and above all else be safe!

Steve Fox served as Chief Design Judge for FSAE-Michigan from 2005 through 2018. He is currently Chief Design Judge for Formula SAE-West. Steve has served as Chief Design Judge at Formula Student Germany, Formula Student Austria, and Formula Student India, is a consultant to the FSAE Rules Committee, and lectures for the SAE’s Industrial Lectureship program: http://students.sae.org/chapters/lectureship/lecturers.htm Steve served as the Design Event Captain at both FSAE Virginia events in 2008 & 2009. Steve has volunteered his time to FSAE & FS since 1999, when he was ‘volunteered’ by Carroll Smith to participate as a Motorsports Design Judge.
