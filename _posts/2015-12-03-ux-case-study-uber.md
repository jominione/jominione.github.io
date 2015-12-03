---
layout:     post
title:      UX Case Study - Uber
date:       2015-12-03 12:00:00
summary:    This will be a first in a series of analysis on user experience (UX) of consumer products and services by tech companies.
categories:
---

This will be a first in a series of analysis on user experience (UX) of consumer products and services by tech companies.


##First-order UX Enhancements

Getting people to adopt new services is hard. UX enhancements are first-order if they can induce users to switch to a new service in of itself.


**Availability** - Uber induces availability through surge pricing. This is a two-edged sword. Basically surge pricing is a mechanism to [increase the number of drivers in an area](https://newsroom.uber.com/2015/09/the-effects-of-ubers-surge-pricing/){:target="_blank"} through the economic incentives of a higher rates. This guarantees, that if you’re willing to pay, you can get a ride wherever you are, whenever you want. The con is people really do not like variable price increases. Taxi’s on the other hand operate on a model where fares are regulated and fixed, which means that taxi drivers can’t respond to increase demand by upping fares and therefore positive incentive for more drivers to jump on the road and satisfy the increased demand. Given the tradeoffs it’s become clear that consumers value availability over price uncertainty for transportation services by voting with their wallets in migrating over to Uber.

**Certainty** - The Uber app provides the ability to track drivers through a real-time map of all drivers within the vicinity and GPS tracking of your driver once a pickup is confirmed. Years ago I was with a group of people who called up two taxis but three showed up because some of us were anxious whether the original call we made would arrive so we called to order another one. Just knowing (and seeing in real-time) whether a driver is coming to pick you up and how far and how long it takes to pickup enhances UX because it reduces stress and anxiety.

The actual wait time is not as important as knowing what the wait time is. However, there’s [evidence](https://newsroom.uber.com/2015/01/uber-expectations-as-we-grow/
){:target="_blank"} to suggest that Uber has raised expectation of maximum wait times over time.

**Safety** - I don’t have stats so I won’t be unequivocal in stating that Uber are safer than taxis, but again, perception is more important than fact in the decision to adopt a new service. Uber enhances the perception of safety by utilising the identity of drivers and being able to attribute bad behaviour to their identity. Once riders confirm a trip they are provided with a photo and licence plate of the driver coming to pick them up to identify them. Each trip is also recorded through GPS tracking. This deters drivers from bad behaviour as their behaviour can be directed attributed to them. In Victoria, Australia, [safety cameras are mandatory in taxis](http://www.taxi.vic.gov.au/drivers/taxi-drivers/driver-safety/safety-cameras-in-taxis){:target="_blank"} but from what I can gather the intention their appears to be to protect the taxi drivers from passengers than vice versa.

In India, Uber has also rolled out a [SOS alert feature](http://newsroom.uber.com/india/2015/04/introducing-an-integrated-sos-alert-solution-for-law-enforcement/){:target="_blank"} feature where the rider can directly alert the police and allow them track you in real-time via GPS.

**Customer Service** - Analogous to safety, Uber is able to induce superior driver customer service by attributing behaviour to driver identity through a reputation mechanism where riders can rate each trip on a 1 to 5 star rating. My understanding is that drivers need to maintain a 4.6 rating to avoid being kicked off the Uber network. You can always provide feedback about your taxi trip but I think the key difference here is the lack of friction in doing so. Unless my taxi trip was particularly bad, the effort of going to report negative feedback is never worth the effort in my mind.


##Second-order UX Enhancements

Second order features are not game changers in of themselves but the sum of the enhancements produce an overall superior UX.


**Ease of hailing** - No phone call required explaining where you’re located and where you’re going or having to street hail a taxi. I live on the first floor apartment building off the main street of an entertainment destination. This is a corridor taxis frequently patrol for pickups yet I regularly observe people futilely trying to street hail taxis. Once saw a couple in the middle of the day (non-peak) trying to wave down a taxi for up to 30-40 minutes. In contrast, through the Uber app it’s just a couple of taps to hail a Uber to your exact location.

**Ease of payment** - No expectation of tipping (relevant in US). No arguments about change, payment methods, or advance deposit.

**Prejudice blindness** - Because there is no pick-up via street hailing, drivers can’t discriminate on the basis of gender, [ethnicity](http://www.abc.net.au/news/2015-10-30/indigenous-elder-jack-charles-rejected-by-taxi-again/6901120){:target="_blank"}, religion etc. This would probably in itself be a big reason for many to change to Uber but it isn’t obvious at first glance unless you’ve experienced discrimination by taxis. See also [this example](http://blavity.com/uber-black/){:target="_blank"}.

**Automated destination locator** - Riders input their destination via the app which is directedly communicated to the driver. Saves an extra step and avoids human error from the process of telling the driver the destination address and then inputting into GPS device.

**Ease of record keeping** - Invoice sent via email (as opposed to printed paper invoice if any provided through taxis) allow for ease in maintaining tax records.

**Record of trip** - Helps deter inefficient trips by drivers and for record keeping.

**Ease in having lost items returned** - If you accidentally leave items in your Uber, you can get in contact with Uber and they will have the driver return the items to you.

**Fare estimator** - The Uber app provides the ability to estimate fare costs according to your location and destination. Because the smartphone is a computer with internet connection, Uber can provide a reasonable estimation of fares by calculating the distance and time a trip will take with real-time data it has.

**Spotify integration** - You can play Spotify through your app in your Uber. Induces feeling of control (even if actual control is limited).

**Third-party app integration** - Many third-party apps are now integrated with Uber allowing you to hail in-app, for example, Zomato.

**Ability to contact inbound driver in-app** - If you need to you can contact driver in-app, for example, placed the currently location pin incorrectly can call driver to advise them of your real location.

**Identifying Driver** - As mentioned previously Uber provides photo, name, and licence plate number of your driver for you to identity them. Avoids the situation of jumping into the wrong vehicle or have someone else ‘steal’ a taxi you ordered.

**Price?** - I don’t believe a cheaper ride is a driving factor in retaining riders as long as fare prices are competitive with the local taxi services. Fare prices are probably important in driving acquisition of new riders but not for retaining them.


##Application of Technology that enhance UX

The tangible service of getting someone from point A to point B use the same technology with an Uber or taxi, namely a car. Hopefully though I’ve made obvious there is more to a car transportation service than the actual transportation itself. The common factor in each of Uber’s UX enhancements is the ability to use the capabilities of the smartphone that everyone has on them. Uber would not exist in this world without smartphones. I will focus on first-order enhancements to to demonstrate this point.

Suppose for the moment that smartphones and Uber didn’t exist and taxis weren’t regulated and instead able to set prices dynamically in response to the ebb and flow of demand, the ability to match availability that Uber currently provides would still not exist for the simple reason that the taxi service doesn’t have access to location-specific demand data via requests for rides in the Uber app using GPS on the smartphone currently provides.

If you call a dispatch service to hail a taxi the dispatch service simply cannot provide certainty that real-time tracking with GPS and the smartphone can.

The key to superior safety and customer service provided by a service like Uber is the ability to deter bad behaviour through the mechanism of identifying a driver and then associate their behaviour with their identity in real-time. Once you have the ability to associate behaviour with identity this deters bad behaviour. The ability to associate behaviour with identity is linked to the smartphone, the act of the smartphone app allocating the driver to rider fills the identity requirement for both drivers and riders. GPS tracking on both driver and rider associates behaviour during the ride with the driver so that any feedback provided by the rider can be associated with the ride and driver.

This is not to say that taxi services before the advent of smartphones don’t have the ability to associate identity and behaviour, but the fact is their ability to do without utilising smartphones is limited. Firstly, the customer has to make a complaint, not in real-time, but after the event. Then the taxi service or customer has the administrative burden of cross checking of records of calls to dispatch, GPS tracking on taxis, witness testimony etc. to associate event, time, and identities. This administrative burden deters feedback which results in limited deterrence effects.


##Conclusion

Hopefully this exercise shows that while Uber does everything a taxi can do, it does more and much better. I would go as far as every aspect of the experience is superior with Uber and that is what’s driving rapid adoption.

The main argument proposed by incumbent taxi services around the world in support of banning Uber from operating is the regulatory burden and licensing costs that the taxi services incur, but Uber doesn’t, means they’re not competing on a level playing field. I think they’re missing the point or being deliberately obtuse if they believe price is the only or even the main thing that Uber is beating them with. If Uber was to adopt the taxi model of employing full-time drivers and owning a fleet of cars as well as associated regulatory costs so that their cost structure was the same as taxis Uber would still be by far a superior service (not withstanding the absence of surge pricing and associated availability).

The Uber UX is designed on the premise we live in a world of smartphones while taxi services, preceding Uber and the advent of smartphones, is premised on a world that doesn’t exist anymore.