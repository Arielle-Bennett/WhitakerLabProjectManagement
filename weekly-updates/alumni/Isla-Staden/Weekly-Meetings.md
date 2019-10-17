# Weekly Meetings

### 2018

* [25 August 2018](#date-25th-august-2018)
* [15 August 2018](#date-15th-august-2018)
* [25 July 2018](#date-25th-july-2018)
* [13 June 2018](#date-13th-june-2018)
* [23 May 2018](#date-23rd-may-2018)
* [8 May 2018](#date-8th-may-2018)
* [25 April 2018](#date-25th-april-2018)
* [14 March 2018](#date-14th-march-2018)
* [21 February 2018](#date-21st-february-2018)
* [18 January 2018](#date-18th-january-2018)

---
### 2017
* [21 December 2017](#date-21th-december-2017)
* [7 December 2017](#date-7th-december-2017)
* [20th November 2017](#date-20th-november-2017)
* [3rd November 2017](#date-3rd-november-2017)
* [4th October 2017](#date-4th-october-2017)
* [20th September 2017](#date-20th-september-2017)
* [1st September 2017](#date-1st-september-2017)
* [18th August 2017](#date-18th-august-2017)
* [3rd August 2017](#date-3rd-august-2017)
* [17th July 2017](#date-17th-july-2017)
* [6th July 2017](#date-6th-july-2017)
* [19th June 2017](#date-19th-june-2017)
* [13th June 2017](#date-13th-june-2017)
* [2nd June 2017](#date-2nd-june-2017)
* [26th May 2017](#date-26th-may-2017)
* [19th May 2017](#date-19th-may-2017)
* [12th May 2017](#date-12th-may-2017)

---

### Date: 23 August 2018

#### Who did you help this week?

* :anguished: I don't know.
  * KW: In person: you advocated for clear git commit usage! Not rewriting history :white_check_mark:

#### Who helped you this week?

* RM with his [kind words](https://github.com/WhitakerLab/BrainNetworksInPython/pull/78#issuecomment-414415183) about the bnip dev guide

#### What did you achieve?

* docstrings for all bnip functions and classes
* generation of sphinx documentation
* developers guide for bnip

KW: Spec-freaking-tacular!! I LOVE IT ALL!!

#### What did you struggle with?

* justifying the changeover from master to dev in bnip. A couple of things have changed and I just don't know why.
  * KW: DETECTIVE WORK COMPLETE!! :mag:
    * participation coefficient -- still to track down - currently writing out the right values in the wrong order!
    * shortest path - typo in the code
    * effiency - new function in networkx - use that one :)
* looking back on this week all I can remember is a hectic blur

#### What would you like to work on next week?

* BIDS : let's crush it. :fist:
  * KW: WOOOOOO - yes! Thank you for sketching this out with me! 
* mindcontrol
  * KW: Yes please :sparkles:

#### Where do you need help from Kirstie?

* Establishing a format for BIDS :moyai:
* Collaborating on mindcontrol to find a way that two users can access it
* reviewing bnip changes
  * :white_check_mark: BOOM - these are looking awesome. I think we're ready to merge once we've made two back up versions!

#### Any other topics

Make sure to take the weekend off!! You've done SO MUCH in the last few weeks!!

---

### Date: 15th August 2018

#### Who did you help this week?

* Honestly, I'm not sure I helped anyone this week. I've been mostly wrapped up in my own work. I did give a friend a few pointers on using git though.
  * KW: That totally counts! And you've been busting your butt to build a kick ass tool that's going to be super helpful for a lot of people :sparkles:

#### Who helped you this week?

* Kirstie has already provided some IMMENSELY helpful feedback on bnip.
  * KW: :sparkles:

#### What did you achieve?

* Refactoring and most of the testing of core bnip modules, along with about 50% documentation, one good tutorial and finetuning the python package setup
  * KW: YEAAAAAH :tada::balloon::cake:

#### What did you struggle with?

* Sometimes struggling with burnout

#### What would you like to work on next week?

* That's up to Kirstie. I'd like to push a bit longer to get a proper release of bnip (specifically I really want to get sphinx autodoc set up and pushing to whitakerlab.github.io + filling in this documentation + finish writing test suites), but there are nspn duties that need to be done before I leave.
  * KW: This all sounds great. Here's a little list of what we've discussed in person:
  * BNIP :white_check_mark: get released to pip, check documentation and see how far you can get with a JOSS submission
  * NSPN: BIDSified UCHANGE dataset - I'll do a first pass re: BEP001, but hopefully you can level it up
  * PyBIDS: Be able to apply the validator using a config file to check UCHANGE dataset https://github.com/INCF/pybids/pull/231 :sparkles:
  * Mindcontrol: Hopefully this is very close and I'd really love this to be working on the HPHI

#### Where do you need help from Kirstie?

* Discuss in meeting
  * KW: BEP001 for BIDS
  * KW: BNIP testing and review of documentation, release checklist

#### Any other topics

KW: Great work while I've been away - I'm so excited for BNIP!!! :scream::heart_eyes::muscle:

---

### Date: 25th July 2018

#### Who did you help this week?

* Added to pybids documentation
  * https://github.com/INCF/pybids/pull/214
  * https://github.com/Islast/pybids/blob/master/examples/pybids%20tutorial.ipynb
  * KW: SO COOL! Well done. You also explained it all to me :sparkles::star2::rocket:

#### Who helped you this week?

* The AMAZING mindcontrol team
  * KW: I have been SO SO SO impressed with all this work! :heart:
  * Currently in https://github.com/Shotgunosine/mindcontrol

#### What did you achieve?

* Mindcontrol working on HPHI (with caveats)
  * Currently not 100% sure if the edits are saved....working on it....
* Call on bep001 + work on creating mpm example
  * KW: Really appreciate all your help with this extension!!
* LightlyProcessedRedcapData CTQ & RCMAS
  * KW: MERGED! So sorry for being slow on this - and THANK YOU!
* guide to pybids
  * KW: :sparkling_heart:

#### What did you struggle with?

* Focusing! I have quite a lot of different things to keep track of

#### What would you like to work on next week?

* BNIP!

#### Where do you need help from Kirstie?

* When it comes to quantitative maps from MPM, should I copy them over from the data_ready folder? And if so what should I do about the fact that they don't have jsons? And if not, how do we recreate them?
  * KW: :scream_cat: Aaaaah! We have to enter BIDS derivatives land!!
  * I'll do that in Seattle - for now please could you set up the directory structures as we sketched on the whiteboard and I'll play with the code to wrap around them :smiley:

#### Any other topics

---

### Date: 13th June 2018

#### Who did you help this week?

* I suppose you could argue that I helped KH be submitting a bug fix pull request to mogutda, but its a very selfserving kind of help

#### Who helped you this week?

* KH did me a massive service by releasing [mogutda](https://github.com/stephenhky/MoguTDA) as a standalone python package
* BM with lacn

#### What did you achieve?

* What did you achieve with your CD time?
	* Massive leaps forward on lacn- all that remains is to write some unit tests and start trying it out on brain data (and maybe speed things up meanwhile)
* What did you achieve with your DAS time?
	* I have not been making any time for this lately
* Where's the sharing BIDS format MRI data paper at?
	* PilotN03 data:
		* Bids formatting complete
		* individual freesurfer derivatives complete
		* mriqc for func images complete
		* mriqc for anat images encountering problems
	* PiloN06 data:
		* Bids formatting complete (validation still fails because mpms are not recognised and also funcs may be mislabelled)
		* Working on slurm script to generate freesurfer derivatives. In theory everything should work, but in practice slurm wants absolutely nothing to do with the tasks i send it :moyai:
	* UCHANGE data:
		* Currently have the scripts drafted. It feels like something that I should submit to slurm because there are so many scans. However bidsification is barely longer than running dcm2nii so it probably wouldn't take longer than a day.
* Where's the Brain Networks in Python paper at?
	* Inspired by `tedana`'s speedy progress, I have been trying to make a big push on bnip

#### What did you struggle with?

* Responses to my MSc applications have been slow coming in. It's left me with this distracting weight on my mind. I was in a bit of a slump for the first week Kirstie was away

#### Where do you need help from Kirstie?

* I'd like to check with Kirstie, about the pilotN06 func images which have been failing bids validation with error
```
2: Bold scans must be 4 dimensional. (code: 54 - BOLD_NOT_4D)
```
and 
```
	3: Nifti file's header is missing time dimension information. (code: 75 - NIFTI_PIXDIM4)
```
Kirstie, do you know how these scans should be labelled?
* Kirstie knows how to use slurm, which I have been struggling with. What I'll probably do is upload my work to the bidsifyingmri repo and we can work on it together there.

#### Any other topics
* When you have a moment, I'd love to hear what happened at the last data management meeting. 


---

### Date: 23rd May 2018

#### Who did you help this week?

* Helped Kirstie and PV with cleaning SPQ data
  * KW: YES - thank you! :sparkles:

#### Who helped you this week?

* AK helped a _lot_ with mindcontrol
  * KW: I'm so excited about this :heart_eyes:
* SN helped with SPQ questionnaire

#### What did you achieve?

* Running mindcontrol on my machine (where it is possible to install meteor)
* Running a singularity container of BIDS/Freesurfer
  * KW: AWESOME
* Cleaning up bnip install instructions for mybinder
* Talked to PP
  * KW: Great - thank you!
* Worked on LightlyProcessed REDCap data
* What did you achieve with your CD time?
	* Applied to QMUL
* What did you achieve with your DAS time?
	* Nothing that I can think of
* Where's the sharing BIDS format MRI data paper at?
	* We are getting very close to having mindcontrol running, the main roadblock being the meteor install
	* All of the pilot data is in BIDS format, up to uncertainty about correct MPM format
	* Maybe time to start working on the U-CHANGE data.
	  * KW: Agreed - lets get going on that while I'm away! :muscle:
* Where's the Brain Networks in Python paper at?
	* still filling out the unit testing
	* documentation needs work
	* some modules still need cleaning up
	* needs linting

#### What did you struggle with?

* Rounding up NSPN interview responses

#### What would you like to work on next week?

* Up to Kirstie
  * KW: You're rather on your own for the next 4 weeks but lets move to bringing all the NSPN data into BIDS format
    * I'll send emails & follow up with MPM team
    * For now see if we can jump into the freesurfer derivatives *without* needing the original data in BIDS format
    * Get the validator working in the browser
    * Run a few BIDS-Apps for fun (to show we can!!) `#goSingularity` :sparkling_heart:


#### Where do you need help from Kirstie?

#### Any other topics

KW: I'm REALLY delighted that you've got so much running on the HPHI! THANK YOU!

---

### Date: 8th May 2018

#### Who did you help this week?

* sent IH a list of journals
* helped dut with new website

#### Who helped you this week?

* JB helped with data interview
* hphi added dcm2niix

#### What did you achieve?

* first data interview
* What did you achieve with your CD time?
* What did you achieve with your DAS time?
   * sent IH a list of journals
* Where's the sharing BIDS format MRI data paper at?
   * bids conversion of PilotN03 data (not completely accurate as multi-echo still presenting a problem)
   * Mindcontrol work ongoing
* Where's the Brain Networks in Python paper at?
    * latest merge to main branch adds sphinx documentation
    * mozilla report ongoing

#### What did you struggle with?

* Understanding Mindcontrol

#### What would you like to work on next week?

* Mindcontrol

#### Where do you need help from Kirstie?

* general neuroimaging expertise

#### Any other topics

What sort of presentation do you want for tomorrow?

---
### Date: 25th April 2018

#### Who did you help this week?

* Helped TC sort out doctor's appointment
* Helped Kirstie with testing file existence

#### Who helped you this week?

* Kirstie being understanding about my jet lag!
* JL for booking this room

#### What did you achieve?

* Wrote up sketch of [data sharing for NSPN](https://hackmd.io/rKn7wWvtTjqm7OYxhSZwvQ?edit)
* Trying to get mindcontrol running on the HPHI. 
    * We'll need a singularity container- it seems like someone on stack exchange has already done this part, if only i could get hold of them.
    	* KW: Send Anisha an email to ask about this - I think she'll know how to do it :smiley:
	    * https://hub.docker.com/r/clowdcontrol/mindcontrol
	* KW: Or, send an email to HPHI support - they should be able to help on this front
    * We'll need some json files (considering writing a little script to autogenerate these from bids format data)
        * KW: comment on issue but then submit if you do this!!
    * more detail [here](https://github.com/WhitakerLab/BidsifyingMRI/issues/4)
* CD time:
    * Applied to Imperial
        * KW: **ACTION** Submit reference!
    * QMUL requires references uploaded by me :neutral_face:
        * KW: **ACTION** Send reference to IS
* DAS time
    * DAS meeting
* Where's the sharing BIDS format MRI data paper at?
    * pilot data missing ses-ucl for subjects `N0604`, `N0605` and `N0606`
        * KW: Go with device serial number instead of name & address :sob:
    * need to run [brain extraction](https://github.com/WhitakerLab/BidsifyingMRI/issues/8)
* Where's the Brain Networks in Python paper at?
    * [Mozilla report](https://hackmd.io/Qp743LHJS7qrtRIFqhQ49A?view) is almost done
         * KW: RIGHT - I'll work on finalising this on Wed 2 May :raised_hands:
	 * Please add character limits so I don't go overboard :grimacing:

#### What did you struggle with?

* I've struggled to get stuff done on the hphi. The computer i'm working on has a wireless card with proprietary drivers and this coupled with the cambridge vpn make for a very slow connection.
    * I have the (new) old computer back now so fingers crossed for clean sailing from now on.

#### What would you like to work on next week?

* I think that this may come from discussion of the direction for NSPN data sharing
  * ACTION FOR KW: **MPM in BIDS** - send email to NW ASAP
      * [NSPN-Handbook/documents/MRI Protocol/Appendix 2 U-Change Sequence Parameters FINAL.pdf](https://github.com/TeamNSPN/NSPN-Handbook/blob/master/documents/MRI%20Protocol/Appendix%202%20U-Change%20Sequence%20Parameters%20FINAL.pdf)
* I believe this week I'm supposed to launch NSPN data interviews
  * https://github.com/TeamNSPN/NSPN-Handbook/issues/18

#### Where do you need help from Kirstie?

* Will discuss in meeting
  * KW: :fire: BIDS & Singularity :fire:

#### Any other topics

---

### Date: 21st March 2018

#### Who did you help this week?

* helped ll prepare for phd interview

#### Who helped you this week?

* Dep. Psychiatry research assistants

#### What did you achieve?

* Bids program feeds commands to terminal
* Much needed bnip updates:new readme,trying to autotest readme code vignettes
  * YEAH! Is it in this [PR #62](https://github.com/WhitakerLab/BrainNetworksInPython/pull/62) or already merged?
  * Let me know where I can help :sparkles:
* Attended research assistants meeting at douglas house, got to know some of the former NSPN research assistants
* What did you achieve with your CD time?
* What did you achieve with your DAS time?
* Where's the sharing BIDS format MRI data paper at?
    * Need to test the pilot data
* Where's the Brain Networks in Python paper at?
    * Progress on BNIP documentation is quite good
    * need to understand why some modules are caught by autodoc

#### What did you struggle with?

* sad feelings :(
  * KW: :purple_heart:
  
#### What would you like to work on next week?

* I have a meeting with GB and SN on Monday morning on behavioural data
* I have some BIDs commands to run!
    * write checks, run checks

#### Where do you need help from Kirstie?

* Would like to know what kirstie has in mind for behavioural data
  * KW: Good call, me too. I'll think about it before the data management meeting.

#### Any other topics

* MELD
  * KW: YES - I'll update you on this when you're back from holiday :japan:
---


### Date: 14th March 2018

#### Who did you help this week?

* the NSPN data management committee

#### Who helped you this week?

* JB gave me loads of important NSPN documentation
* KW and PJ gave me a lot of help with the presentation

#### What did you achieve?

* NSPN meeting presentation
* What did you achieve with your CD time?
    * Sent draft of personal statement to reference writers
    * did some work on implementing algorithm
* What did you achieve with your DAS time?
    * not much
* Where's the data management presentation at?
    * done! 
    * KW: WOOO!! :sparkles:
* Where's the Brain Networks in Python paper at?
    * in progress this week!

#### What did you struggle with?

* stage fright
  * KW: Way to go pushing though!! :muscle:

#### What would you like to work on next week?

* Plan to meet with GB next week
* would like to finish bidsifying what can be bidsifyed

#### Where do you need help from Kirstie?

* Looking forward to having Kirstie back from strike
  * KW: I'm BAAAAACK - finally!

#### Any other topics


---

### Date: 21st February 2018

#### Who did you help this week?

Replace this text with a one/two sentence description of who you helped this week and how.

#### Who helped you this week?

Replace this text with a one/two sentence description of who helped you this week and how.

#### What did you achieve?

* DAS time?
    * generated figures for methods section
    * rounded up some BMC 2016 no-das examples for Iain to look at
    * I just want to mention that I feel like last week's das meeting was really good.
        * KW: GREAT! I agree :sparkles:
* Where's the data management presentation at?
    * Slow start, but following last week's conversation with PJ I have a few screenshots
* BIDS format MRI data paper:
    * I think we're doing okay
* Where's the Brain Networks in Python paper at?
    * [JOSS paper branch added -I should add this to the main repo](https://github.com/Islast/BrainNetworksInPython/tree/josspaper)

#### What did you struggle with?

* Getting things done. I feel deeply disorganised lately. Progress on NSPNhandbook is slow because I've sort of run out of ideas or at least easy things to do. Progress on CD is slow because I'm so daunted by going back to studying. We've been getting a lot of BNIP questions which has made me focus on that more than I intend to. I've also been switching between computers a bit :yuck:

#### What would you like to work on next week?

* Would love to find time to work with Kirstie on the data management presentation
  * KW: Tuesday 27th & Tuesday 6th :muscle:
* Want to fully BIDsify the pilot data (an hour to a day, depending on hitches)
  * KW: Thursday 22nd :punch:
* I would love to make better docs for BNIP, so that our users can reach beyond just using the tutorial. (/ maybe a better tutorial)
  * KW: Makes sense! Thursday 1st!! WOOOOOO :star2::star2::star2:
* CD: I mean to get the landscapeofcomplexnetworks algorithm sorted out by the end of the week, only problem is that I'm not sure if there's a mistake in the paper.
  * KW: As discussed, make the figures from the paper, check with BMh and then email the authors if you're still stuck!
* More NSPN: I feel I should finish reading all the NSPN publications, in order to do my job better
  * KW: Meh - only if you want to :confused:
* Kirstie mentioned making a budget for the brain networks satellite of netsci. I should do that!
  * KW: Yes please!

#### Where do you need help from Kirstie?

* Data management presentation
* get BIDS data in the right places

---
### Date: 18th January 2018

#### Who did you help this week?

* I am promptly going to help the Cambridge VPN service desk by detailing how I set up connection from a Ubuntu 17.04 machine
  * KW: Excellent :+1:
* KW: Huge amout of work for the DAS project!!! :star2:

#### Who helped you this week?

* Whole DAS team + G
* Feedback from GP on datamanagement resource

#### What did you achieve?

* DAS sprint
* meeting with GP
  * KW: REALLY valuable - well done :muscle:
* connecting to the HPHI from Cambridge and connecting to the Cambridge VPN from London
  * Works, but everything goes very slowly
  * KW: Well done, look into connecting via BCNI

#### What did you struggle with?

* I do not know what I am doing
  * KW: Mostly watching netflix waiting for your body to feel better!! Take care of yourself.
  * For next meeting make Open Canvas plans for:
    * NSPN Handbook presentation
    * NSPN BIDS format MRI data
    * Brain Networks in Python paper - JOSS

#### What would you like to work on next week?

* If technical skies clear we can get started with BIDS
  * KW action: send travelling heads data

#### Where do you need help from Kirstie?

* BIDS
  * KW: :+1:

#### Any other topics

* We should talk about my meeting with BM before Christmas
  * KW: Great summary! Go forwards!

---

### Date: 21st December 2017

#### Who did you help this week?

* someone in the open leadership chat - directed them to open humanities resources

#### Who helped you this week?

* LV and KW as per usual, the former with practical help (and practical advice) and the latter by good feedback and making time for me despite the DSG
* UT!

#### What did you achieve?

* Moz blog post
* Data management welcome pack
* couple of updates to brain networks in python
  * KW: YEAH! Merged :sparkles: https://github.com/WhitakerLab/BrainNetworksInPython/pull/52
* What did you achieve with your CD time?
  * Met with UT
* What did you achieve with your DAS time?
  * not much


#### What did you struggle with?

* Figuring out the requirements of the NSPN welcome pack

#### What would you like to work on next week?

* Christmas :christmas_tree:

#### Where do you need help from Kirstie?

* Haha, hopefully I can do this without help

#### Any other topics

---

### Date: 7th December 2017

#### Who did you help this week?

* tried to helped J with brain network visualisations
  * KW: Why say "tried" - IS: because the code in matplotlib isn't as nice so actually the plots were made in matlab instead!
  * KW: Still good to try!! :sparkles:
* contributed to a hack day
  * KW: I had *so much fun* and was really impressed with your [`get_papers`](https://github.com/ContentMine/getpapers) skillz :computer:
  * Would be nice to write up a little blog post about this...but who has the time ??
    * Maybe we could do a mini hack afternoon to pull the work together? (possibly including the team at ContentMine)

#### Who helped you this week?

* LV helped me with everything NSPN
 * KW: Fantastic :dancer:

#### What did you achieve?

* Made some contributions to the NSPN repo and got myself set up on Redcap, hphi
  * KW: GREAT! Another thank you to LV :hibiscus:
* Got that [green build passing badge](https://travis-ci.org/WhitakerLab/BrainNetworksInPython) on bnip
  * KW :tada:
* Completed Mozilla Open Leadership Training
  * KW: :sparkles: :sparkling_heart: WELL DONE
* What did you achieve with your CD time?
  * Not so much, but the last weekly meetings was all about this
* What did you achieve with your DAS time?
  * Labelling articles with their das mandate status
    * KW: :muscle: GREAT!

#### What did you struggle with?

* Staying focused

#### What would you like to work on next week?

* Blog post about Mozilla Open Leadership & Mozilla Science Lab Mini Grants - your experience with Brain Networks in Python.
* Continue with the same balance of BNIP/NSPN/CD & DAS as in November :white_check_mark:
* Keep working on welcome pack for NSPN

#### Where do you need help from Kirstie?

* Better vision for NSPN
  * KW: good point - lets find time next week to build an agenda for the NSPN DM meeting

#### Any other topics

* Holiday over Christmas
  * KW: Good point - email Psychiatry HR to find out the rules!
  
---

### Date: 20th November 2017

#### Who did you help this week?

* Helped J with git
  * KW :sparkles: THANK YOU - please update the onboarding repository with any resources you think are useful!
  * Really interesting that there's a need for sharing this knowledge.
    * What about running a Cut, Copy, Paste session? A "school fair" day?! Can we get the doctoral students to show off their skills and share with each other?
    * KW: I think this needs to be a student lead idea but I AM SO HAPPY to help out in anyway.
    
#### Who helped you this week?

* TF, Kirstie, LL helped me with me with my msc application
  * KW: FINGERS CROSSED
* The delightful pull requester on bnip who helped with the Travis CI
  * KW: YAAAAY :tada::balloon::tada: 

#### What did you achieve?

* Surviving OpenCon
  * It was fun, but very overwhelming!
  * KW: Interesting to compare maths research openness (on arXiv, no data) with open education for maths - how to learn is siloed etc, also the need for inclusivity and re-defining success (or who is good) in maths.
* BNIP regression tests now save hashes instead of files
* CD: Applying to Oxford MSC
* DAS: Converted data to csv, included speeding up the script that does that
  * KW: YEAAAAAH - thank you - super valuable
  
#### What did you struggle with?

* Being too busy! I'm really grateful that I got to go to OpenCon, but man was I tired afterwards

#### What would you like to work on next week?

* Time to give some love to NSPN- particularly getting set up, getting in touch with the people I need to be in touch with etc.
  * Great - see the notes on the board :smile: Let's build the ***Welcome to NSPN*** website/wiki
* I have also decided to apply to the Turing phd programme so that will need some time
  * Deadline: 30th November
  * Meet/email potential supervisors
  * Sort out referees
  
#### Where do you need help from Kirstie?

* I think I will need a lot of help from Kirstie while I get set up with NSPN but mostly just to answer questions

#### Any other topics


---
### Date: 3rd November 2017

#### Who did you help this week?

* Helped Abby with putting up posters for the Mozilla Open Leadership zone, also helped out at the desk at MozFest!
* KW: Deeply helped me out hosting Erin when she visited - so glad you clicked and got on well!

#### Who helped you this week?

* Loads of people helped me!
  * Christos helped me get set up before my session!
  * Natalia gave me a hug
    * KW: Sparkles :sparkling_heart:

#### What did you achieve?

* MozFest session!! Really worried about it in advance but it was really fun. People learnt about the project.
  * KW: YES! :100::100::100:
  * KW: Particularly proud that this was so outside of your comfort zone.
  * Also really great to meet the other open leadership cohort!
* Career development: Got a job!
  * KW: WOOOO Way to go! :sparkles: Super excited!
* Significant progress in Brain Networks in Python!!
  * Eg: Found out during MozFest that new version of NetworkX is incompatible with old version. So glad to have figured that out!
    * KW: YEAAAAAH - blog post?
  * Implemented regression tests
  * Got a good roadmap for refactoring - meeting on Monday to discuss in detail!
* Progress on DAS project management
  * Sticking to 1 day per week & moving forwards
  * KW: Great - and I'll take on some of the visualisations & descriptions :muscle:
* Career development: drafted application for masters program - deadline soon...gonna be fine
  * KW: AWESOME - let me know if you have any questions
    * Make sure to focus on getting your letters of recommendation ready to rock!

#### What did you struggle with?

* Nerves :confused:
* Anger :rage:
  * Stupid computer isn't working & stupid advice from tech support isn't helping
* Being poorly :mask:
* Politics
  * KW: Very true - hopefully we're moving in the right direction

#### What would you like to work on next week?

* Getting ready for OpenCon
* Learning about the NSPN data!
* Catching up w Kirstie on Brain Networks in Python
  * Excited to set up a bunch of issues! :sparkles:

#### Where do you need help from Kirstie?

* Big meeting already planned to talk about the vision & roadmap for Brain Networks in Python
* Onboarding for NSPN data management
  * KW: arranged meeting on Thursday morning :smiley:

#### Any other topics

---

### Date: 4th October 2017

#### Who did you help this week?

* helped SM fold recycling boxes - this isn't particularly charitable, it's in my top 20 favourite passtimes
* fixed kirstie's chair again -  also top 20
  * YAAAAS - thank you :sparkles:

#### Who helped you this week?

* Kirstie fixed the Travis CI pull request that was driving me mad! Thank you Kirstie :sparkles:
* TH raised a lotta good points on mozfest

#### What did you achieve?

* Got Travis CI working for BNIP and pr-ed first tests
* blog post for bnip package name
* Overview of new das data
* Progress in :
  * redrafting bnip readme
  * Msc research/ writing applications
  * budget for opencon

#### What did you struggle with?

* Just feel like I'm wading through treacle sometimes

#### What would you like to work on next week?

* BNIP
  * KW: This is getting so exciting! :grinning: :tada:
* budget for opencon!! (another half hour max)
  * KW: Great - send along & recommend staying at OpenCon hotel
* DAS: wrangle subj info (a morning?)
  * KW & IS: Write up algorithm for assigning subjects
* CD: apply to NSPN job (no idea)
* prepare for mozilla democall (this is something I can be thinking about when working on bnip readme etc. Will want to practice it on Kirstie a couple of times (~5 mins))
  * KW: :sparkles: Ready to rock - practise scheduled for 3pm Friday :grimacing:
* prepare for mozfest (a while)

#### Where do you need help from Kirstie?

* das subject wrangling: I need to get the subjects out of xml and into something easier to 
	interact with in python. Once this is done, see Kirstie.
* mozfest session + mozilla democall

#### Any other topics



### Date: 20th September 2017

#### Who did you help this week?

DAS project to get full dataset :ok_hand:

#### Who helped you this week?

TH, thanks for mentoring!
  * KW: :sparkles:

#### What did you achieve?

* We reached a decision on what to do with the das project.
* Thinking very hard about BNIP
* KW: Accepted to OpenCon! :tada:
* KW: Accepted to MozFest! :sparkles:

#### What did you struggle with?

* video call technology
* explaining the issues with the pubtype refinement of the das data
  * KW: As discussed in meeting, send email to A & J w numbers dropped by various criteria
  	* After a second look at the API, although a large number of BMJ articles do only have this "journal article" tag I'm not convinced that many of them are what we would want to count anyway. I'm therefore going to stop worrying and let A go ahead and filter by "research article".

#### What would you like to work on next week?

* Give my love and attention to BNIP
  * First off I'd like to set up some regression tests so that we can know if we're breaking things

#### Where do you need help from Kirstie?

* We should discuss how to manage BNIP
  * KW: Made @Islast admin of [WhitakerLab/BrainNetworksInPython](https://github.com/WhitakerLab/BrainNetworksInPython)
  * KW: Create issues 1) how to get contributors, 2) plans for MozFest
  * KW: Check out https://github.com/uwescience/shablona

#### Any other topics

* Build budget for travel to OpenCon


### Date: 1st September 2017

#### Who did you help this week?

* I helped LL with some topology questions in his dissertation
  * KW: NICE! :sparkles:

#### Who helped you this week?

* Kirstie and BM with that thing where you can tab everything at once- I had no idea. 
  * KW: Aaaahahaha - awesome :raised_hands:

#### What did you achieve?

* I've cleaned up a lot of the work I have done on the DAS project.

#### What did you struggle with?

* This week has been a heavyhanded lesson in "tidy up and explain while you go along" and "explaining what you've done takes longer than you expect it to"
  * KW: Aaaaamen. Keep up the good work though. It's so valuable - thank you.

#### What would you like to work on next week?

* TBC
  * KW: Scheduling work for new responsibilities as discussed in meeting.

#### Where do you need help from Kirstie?

* Planning ahead
  * KW: As discussed in meeting.
  
#### Any other topics

-----

### Date: 18th August 2017

#### Who did you help this week?

* I proofread Kirstie's newsletter.
  * KW: YAAAAY! Thank you! :sparkles: :balloon:
  * KW: and you gave an awesome presentation! :star2:
  * KW: AND you gave R a bunch of interesting resources (even if they aren't all that helpful)

#### Who helped you this week?

* R gave me some advice on topic modelling
* HH gave me a lot of suggestions on document clustering
* Kirstie gave me guidance with my slides

#### What did you achieve?

* Report on the das project
  * KW: which was great! Well done!
* Comparing the das datasets + report
  * KW: including a fun play around with topic modeling which looks fun!

#### What did you struggle with?

* Getting everything done on time

#### What would you like to work on next week?

* Methods of clustering das
  * Topic Modelling- interesting but not super useful
  * minhash?
  * blue scores/ngram distributions
  * doc2vec ([has gensim implemenatation](https://github.com/RaRe-Technologies/gensim/blob/develop/docs/notebooks/doc2vec-IMDB.ipynb))
    * KW: Take a look at this github repo if it's of any use! https://github.com/CDIPS-AI-2017/pensieve
* I want to get all of the das work into shape, so that we can put it aside until the new data comes in.
  * KW: YES - lets set 1st September as a day to move onto a new schedule of work. DAS won't be done, but you can deprioritise it.

#### Where do you need help from Kirstie?

* I would love to work with her on the data availability statements, but if she's busy I think I can move forward without her. There are a lot of people at the Turing with expertise in relevant areas who I could ask
* I'm going to keep polishing the jupyter notebooks I've been using for analysis and I will probably ask her some time next week to give feedback
  * KW: I'm in Toronto next week, but lets try for a collaborative doc that I can add comments to

#### Any other topics

* Maybe we should discuss when to move on from focusing on DAS to focusing on BNIP
  * KW: Yes - sorry to rush out on you. High priorty conversation for when I'm back
* How does Kirstie generate her markdown calendar? It's super usfeul.
  * KW: check out [NewMonthForWhere.ipynb](https://github.com/WhitakerLab/WhitakerLabProjectManagement/blob/master/Kirstie-Whitaker/NewMonthForWhere.ipynb)

- - -


### Date: 3rd August 2017

#### Who did you help this week?

* I recommended the API to B on the fragile families project
  * KW: That's great :tada:

#### Who helped you this week?

* Kirstie, big time. Gave me so much help on my mozfest, mozilla open leadership and opencon applications
  * KW: Woooo hooo! :sparkles:
    * Can we add these to the resources page for the website?
    * To do for KW: merge in Mozilla mini grant PR
* AH sent over some new data availability statements

#### What did you achieve?

* Three applications! oof.
  * KW: :muscle: WAY TO GO.
* Took a look at the new das data

#### What did you struggle with?

* Writing applications- every time I read some thing back I flinch

#### What would you like to work on next week?

* The das project seems to have almost spiraled out of control. Needs explanation now, much more than analyses
  * KW: Sounds like a great plan. Hold [Bloom's Taxonomy](https://en.wikipedia.org/wiki/Bloom%27s_taxonomy) in mind and "aim to write a shorter letter" so we can communicate all the work you've done clearly.
  * Build the report in either LaTeX or markdown - whichever works best.

#### Where do you need help from Kirstie?

* I could use some guidance on what the EPMC team needs to know
  * KW: Great question - as discussed, stay focused on the errors in DAS & get those fixed first

#### Any other topics

- - -

### Date: 17th July 2017

#### Who did you help this week?

Gave moral support to KZ on using content mine

* KW - AWESOME - super helpful

#### Who helped you this week?

Kirstie and BmcG helped me with data analysis

#### What did you achieve?

* Introduced myself to PMR
* Had a useful meeting for das-project
* Have a full and useful csv now

#### What did you struggle with?

* I think I feel out of my depth with this analysis in a more serious way than usual
  * KW: This is a very appropriate feeling! We're asking you to do a whooole bunch of new things. And with great power (big data, big statistical models) comes great responsibility! It's very easy to do crazy things with statistics!!

#### What would you like to work on next week?

* There are plenty of remaining csv analysis questions.
* I find myself wondering about potential usefulness of contentmine
* I really would like to try and apply some data science to separating positive and negative das

#### Where do you need help from Kirstie?

* Advice
  * KW: YOU. ROCK. And are doing an amazing job. And all your caution around the analyses are spot on :smile:

#### Any other topics


### Date: 6th July 2017

#### Who did you help this week?

* Fixed Kirstie's chair so it doesn't lean back
  * KW: ***SO*** helpful.
* I think I lent someone a pen
* I made a document collecting my questions with AH's answers so that BMcG wouldn't have to look back and forth through the email chain
  * KW: Really, seriously, incredibly useful. Great initiative. Thank you :balloon:

#### Who helped you this week?

* AH by responding to my questions so thoroughly
* Kirstie's excellent debugging suggestions (thank you for letting me bug you so much):blossom:
  * KW: No problem! Very happy to help out :smile:

#### What did you achieve?

* Got some very basic analysis going on the das project
* Have made little improvements to the regression test script

#### What did you struggle with?

* Frustration
* Computer directed anger management issues
* productivity...

#### What would you like to work on next week?

* It's time to start analysis on the das dataset
* I try not to neglect BNIP
* learning about content mine

#### Where do you need help from Kirstie?

* Looking forward to our meeting to discuss analysis next Thursday!
* Would like Kirstie to look over the testing scripts

#### Any other topics


### Date: 19th June 2017

#### Who did you help this week?

This week I actually did move the mugs left in the sink to the dishwasher.

* KW: *sigh* people suck. But thank you! :raised_hands:

#### Who helped you this week?

BMcG gave me a lot of support writing the DAS report. Also my brother and dad let me test run my explanation on them. It's good to try and explain what you're doing to other people!

* KW: AWESOME! That's great! :clap: :sparkles:

#### What did you achieve?

* Finished the report
  * KW: It looks fantastic - super helpful - well done :balloon: :cake:

    These two sentences make me SO HAPPY:
    > We've checked the contents of ten data-availability statements against the articles online, all ten were indeed present in the online text.  
    > We've also checked seven articles without this tag to make sure they didn't have data-availability statements. They did not.
* Started reading up on brain network analysis

#### What did you struggle with?

* Microsoft office :boar:
  * ***Action for KW***: Get Isla a copy of the evil office. :heavy_check_mark: Done - sent invite from personal account that can be shared with up to 5 people.
* Mostly this was a good week
  * KW: AWESOME :star2:

#### What would you like to work on next week?

* I have a short program to write for DAS project
* I need to finish the jupyter notebook that I started to show problems with the EPMC API, although we may be able to ask them directly now
* Get a testing script started
* I think now is a good time for me to learn some more about network neuroscience

* KW: These all sound great - if you want to implement anything with the GAP study data that would be super fun, but keeping on in this general direction is perfect.

#### Where do you need help from Kirstie?

* not sure, maybe with network neuroscience resources? I've been using the book and reading list
  * KW: I think I need to get you some feedback on the blog post because that would be great to ship out and there are a few edits I'd like to see. Totally my fault that they're not submitted yet :eye_roll:

#### Any other topics


### Date: 13th June 2017

#### Who did you help this week?



#### Who helped you this week?

MO gave me an intro to testing code

#### What did you achieve?

* Determined why there are so many 0 reference articles!

#### What did you struggle with?

* Replace this text with a bullet point list of where you struggled this week.
* It's ok if your list is only one bullet point long!

#### What would you like to work on next week?

* Finish writing DAS report
* If I get time I'd like to start testing BNIP

#### Where do you need help from Kirstie?

* If possible, ask R about the incorrect reference counts on the API


### Date: 2nd June 2017

#### Who did you help this week?

Replace this text with a one/two sentence description of who you helped this week and how.

#### Who helped you this week?

Replace this text with a one/two sentence description of who helped you this week and how.

* These are always the hardest two. Why? Is there something wrong with me?

  * KW: No! Definitely not wrong with you. These are super odd questions to ask (but important I think!) Keep an eye on all the ways in which you're helping out. Moving forwards on the DAS project and the Brain Networks in Python code is really amazing!

#### What did you achieve?

* This has been a slow week, but I familiarised myself with the eupubmed API and with contentmine.
  * KW: GREAT! [Just keep pushing](http://matt.might.net/articles/phd-school-in-pictures/) :smile:
* By end of today I'll upload the new blog post!
  * (KW: Moved from plans for next week! YEAH!)

#### What did you struggle with?

* One thing that's been tricky this week is working without with Kirstie (since she's out of the country). I have relied on being able to go over to her desk and bug her.
  * KW: Yes. This is definitely harder. Let's see if Gitter is useful:
    * General questions in the [WhitakerLab Lobby](https://gitter.im/WhitakerLab/Lobby)
    * Brain Networks in Python questions in the [BrainNetworksInPython](https://gitter.im/WhitakerLab/BrainNetworksInPython) room :smile:

#### What would you like to work on next week?

* Well there're some things I ought to do for the DAS project- i.e producing a presentation about my findings on the pubmed api/dataset/article contradictions (this from last week :moyai:) and taking a look at the new dataset.
  * KW: I think this is the really important thing to cross off the list by the next time we talk. Otherwise it's going to just keep hanging over us :unamused:
* I would like to sort of get a start on testing next week. I *want* to pull everything in Brain Networks in Python together and start permuting/ making ever prettier figures, but it would be wiser to get the hang of testing before I rush into everything else.
  * KW: Yes, lets go for a marathon not a sprint on this front :fist:

#### Where do you need help from Kirstie?

* I need her to pedal hard and raise good money for aids! :mountain_bicyclist::leaves:
* It would be great if she could give me some pointers on learning testing
  * KW TODO: Put you in touch with Martin

#### Any other topics



---

 ### Date: 26th May 2017

 #### Who did you help this week?

 Hmmm.

* KW: Practical help of refactoring the Brains Networks in Python code is helping *everyone* who wants to use the code in the future!
     (which may only be a couple of people, but that's still REALLY helpful)

#### Who helped you this week?

 Kirstie gave me a lot of life-saving help with the Brain Networks in Python stuff

#### What did you achieve?

* Confirmed innacuracies in xml data for DAS
* Got a lot of things working nicely in Brain Networks in Python

#### What did you struggle with?

* Although I've found it easy to describe graph theory and python, I'm struggling to talk about the motivations for this sort of work
* Earlier in the week with the DAS issues I lost optimism

#### What would you like to work on next week?

  * I've really enjoyed the Brain Networks in python stuff. It seems to me that there is a lot more work to be done there in terms of modularising and introducing tests. (weeks plural?)
    * KW: Action for Kirstie - introduce Isla to Martin O'Reilly because testing would be AMAAAAAZING :sparkles: :sparkles: :sparkles:
  * I'd like to take a shot at the pubmed API (a day or two)
  * I should write up the data checking I did so that BMcG can pass it on to IH (a few hours)

 #### Where do you need help from Kirstie?

  * Let's really think about this. I will still probably need to ask a bunch of questions about these scripts - via github issues as discussed.
  * I guess I'm a little afraid that I'll run out of stuff to do, especially if the DAS project doesn't work out.
  * KW: Some ideas:
    * Visualise the correlation matrices sorted in different ways - eg by module or topologically by x, y, z
    * Use Force Atlas layout to visualise the topology of the network
    * Permutation testing between groups (Big job! Woooo!)

#### Any other topics

 Think about https://science.mozilla.org/blog/mini-grant-cfp!


### Date: 19th May 2017

#### Who did you help this week?

* Helped HH by proofreading his fellowship application
  * KW: VERY helpful!

#### Who helped you this week?

* BMcG gave me a lot of good advice about what to expect from articles data, techniques to use with the large xml files.
  * KW: Great stuff

#### What did you achieve?

* For [WhitakerLab issue 19](https://github.com/WhitakerLab/WhitakerLabProjectManagement/issues/19) I got the first two wrappers working, have been writing my comments as I go :carousel_horse: :sparkles:
  * KW: WAY TO GO! Thank you!
* For the DAS project I learnt quite a lot about the data, produced some nice graphs. :art:
  * KW: They look great...although not what we'd expect from the data :unamused:

#### What did you struggle with?

* Understanding the structural covariance network analysis with respect to brain science
  * KW: Definitely difficult if you can't access the papers!! Try [Unpaywall](http://unpaywall.org/) and see if there are green open access versions of the papers. Here's a [bunch of information](http://osc.cam.ac.uk/open-access) about open access at Cambridge if you're interested.
* TypeErrors :moyai:
  * KW: WELL DONE!
* I feel that this week I got bogged down a lot in programming issues
  * KW: Just keep pushing! :punch:

#### What would you like to work on next week?

* I'd like to get the structural covariance blog written up (:watch: a couple of days. There is quite a lot to do here, not just in terms of getting the visualisations going, but also explaining (and understanding!) what is going on.
  * KW: GREAT! Thank you.
* For the DAS project I still need to check a sample of the data for accuracy (:watch:  a few hours, I fear)
  * KW: Yes, great plan. I'd suggest starting with papers that have a lot of references and are open access. Eg from PlosOne.
* Try to estimate how long each task will take.
  * KW: If you figure this out, please do let me know :neutral_face:

#### Where do you need help from Kirstie?

* Would benefit from talking about structural covariance networks, where the data comes from etc. (:watch: maybe an hour some time next week?)
  * KW: absolutely.

#### Any other topics

---


### Date: 12th May 2017

#### Who did you help this week?

* I did some analysis of the DAS data that has been interesting
  * KW: Yaaaaay! Super exciting!
  * KW Q: What is Beautiful Soup!? Where's the name from?
    * IS: It seems to come from Alice in Wonderland, see [here](http://www.authorama.com/alice-in-wonderland-10.html), I'm still not really sure why.

#### Who helped you this week?

* :sparkles: Kirstie :sparkles:
* Hieu and Darren helped me by giving me material for the Whitakerlab blog.
* Barbara helped a lot yesterday with getting me started on the DVS project
* Amerik gave me a pass to the office!
* People in general have been very friendly

#### What did you achieve?

* Introduced myself to a lot of people!
* Started an introduction to Neuroimaging reading list
* Got a good start on processing DVS files
  * KW: YAAAAY! :sparkling_heart:
    * Processed xml file, got distribution of dates of articles, journal titles look sensible! YAAAAY (again).

#### What did you struggle with?

* Convincing people to say something for the blog
  * KW: Possible suggestion for next time is to not make the write up of the conversations public, it could be a report rather than a public facing blog post.
  * Interesting challenge between not wanting to bother people and writing something that (potentially) many others will see!
* Understanding neuroimaging. I don't feel like I've gotten very far
* Time management? Handling having a lot of different things to think about (and remember to do!)

#### What would you like to work on next week?

* Finishing running and wiki-ing structural covariance analysis (+ maybe a python notebook?) (a few days I think)
  * KW: Work in jupyter notebook to demonstrate use of code. Copy over data from PNAS paper to use as example input etc. Can also be used for code tests (either now or in the future).
* Exploring the DVS dataset (depends how far I want to go)
  * KW: Keep exploring! See what's there!
  * Next step is to write out the data in a cleaner format (eg csv file). Meeting planned with Barbara next week.
  * Possibly move on to doing analyses (although depends on how much time the cleaning takes).


#### Where do you need help from Kirstie?

* With the structural covariance analysis- in particular I'm wondering how much detail to go into in explanation.
  * KW: See above about jupyter notebook - best explanation is through demonstration! If you can write up a blog post that has some screen shots of the jupyter notebook that would be great.
  * Try not to write too much! The goal of the blog post is to help readers understand why they might want to do structural covariance network analyses. Sections might include:
    * Motivation
    * Building the network
    * Creating a graph
    * Calculating global and nodal measures
    * Visualising the network
  * There's a challenge for the blog post around how to include a small amount of useful background information motivating *why* we would want to do structural covariance network analyses....take a look at the Network Neuroscience reading list - in particular Alexander-Bloch et al's Nature Review's Neuroscience paper in 2013:  [doi: 10.1038/nrn3465](http://www.nature.com/nrn/journal/v14/n5/full/nrn3465.html)
    * Side note: please add this paper to the Network Neuroscience reading list.

#### Any other topics

What's going to happen in June? How should I spend my time while Kirstie's is traveling?
* KW: Take ownership of DVS project - really explore the data and look for insights. Also potentially explore network measures between two groups (probably by implementing permutation test between them).

---

## Template

### Date: [INSERT DATE OF MEETING]

#### Who did you help this week?



#### Who helped you this week?

Replace this text with a one/two sentence description of who helped you this week and how.

#### What did you achieve?

* Replace this text with a bullet point list of what you achieved this week.
* It's ok if your list is only one bullet point long!
* What did you achieve with your CD time?
* What did you achieve with your DAS time?
* Where's the sharing BIDS format MRI data paper at?
* Where's the Brain Networks in Python paper at?

#### What did you struggle with?

* Replace this text with a bullet point list of where you struggled this week.
* It's ok if your list is only one bullet point long!

#### What would you like to work on next week?

* Replace this text with a bullet point list of what you would like to work on next week.
* It's ok if your list is only one bullet point long!
* Try to estimate how long each task will take.

#### Where do you need help from Kirstie?

* Replace this text with a bullet point list of what you need help from Kirstie on.
* It's ok if your list is only one bullet point long!
* Try to estimate how long each task will take.

#### Any other topics

---
