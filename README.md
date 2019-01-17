# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018
## Homework 1:  Rational Paranoia

### Student Information

_Student name_: Yorke Rhodes IV

_Student NetID_: yr8

## Problem 1
- Scenario: You oversee the football **stadium** at a university whose team is frequently ranked among the best in the country.
- Assumptions:
  - it is game day (stadium is full of players and fans)
  - the visiting team is a fierce rival, and many visiting fans have come to the stadium for the day
  - there is a tailgate prior to the game which many fans are drinking at
  - there are many families in attendance with children
  - the university stores their trophies and sells memorabilia / merch via vendors in the stadium
- Assets:
  - **players**: the players are likely viewed as the most valuable asset by the university because they attract fans, which in turn means revenue for the school --> likely these players are extraordinary due to the teams ranking, which also could bring sponsor opportunities
  - **home team fans**: the home fans are a huge revenue source for the university, which is likely providing security for events at the stadium
  - **store items**: the items for sale within stores should be protected from vandals/thieves
  - **the field**: the field needs to be protected on game day to prevent damages/interference
- Threats:
  - **play interference**: someone could run onto the field in the middle of the game
  - **vandalism/thievery**: because of such a densely populated event, catching an individual in the stadium stealing from a store or damaging school property is a huge challenge
  - **drunk belligerents**: combination of intense sporting events and tailgating leads to intoxicated attendees which might cause fights or commotion
  - **emergency/terrorism**: with such a tightly packed space like a stadium, an emergency would necessitate swift evacuation which threatens the security of players, fans, etc.
- Countermeasures:
  - **security checkpoints**: security checkpoints at the entrances of the stadium and all field entryways which verify tickets/identification could prevent major terrorism situations and field invasion; this is costly (number of security guards * wage), but the benefits of protecting against these worst-case scenario situations outweigh this cost
  - **locked cases/theft beepers**: vendors and expensive memorabilia can be protected from vandalism and theft with locked display cases/theft beepers; this type of technology can be expensive and is only a justified cost if the value of the assets signficantly outweighs the one-time investment
  - **partitioned seating sections**: different sections of seating could be allocated for different fan types to protect against fighting/offer families comfort from drunks/rowdy students; this comes at almost no cost and reduces the number of security threats in the seats significantly 

## Problem 2
- Scenario:  As head of IT for an international law firm, you are responsible for a **document management system**; some documents stored there are about sensitive legal, financial, or
political matters.
- Assumptions:
  - due to the international nature of the firm, the documents must be accessible online
  - priority above all is preventing leaks of sensitive information
  - some sort of organizational hierarchy exists within the firm which defines tiers of credentials for accessing documents from this management system
- Assets:
  - **sensitive physical documents**: documents containing sensitive information in a physical format (ie printed on paper) need to be protected and stored securely or disposed of once digitized
  - **document scanners**: scanners used to digitize sensitive documents could also contain this sensitive information in some form or another (ie scan history) 
  - **hosting servers**: servers used to host the digital versions of documents need to be monitored/protected to prevent leaks/misuse of sensitive data
  - **system credentials**: credentials given to employees for access to the digital versions of documents need to be protected
- Threats:
  - **physical snooping**: during/prior to scanning, the documents exist physically and anyone with a camera or a physical connection to the scanners can intercept all of the sensitive information 
  - **loss/leak/abuse of credentials**: employees can very easily lose their credentials, potentially expose them without knowledge of doing so, or even sell them for profits
  - **misuse of system**: an employee could very easily violate security protocol and send documents over the network outside of the security defined within the document management system 
  - **internet snooping**: data in document management system will need to be passed between office locations, and can be viewed by any snoopers on the network
- Countermeasures:
  - **prevent extraction**: system could be designed in such a way to only allow content to be viewed through it, without downloads/extraction of sensitive data => will never be inadvertently stored outside of the system; this has a somewhat high developer cost but the benefit satisfies the main priority
  - **encrypt online, decrypt offline**: the raw data should never exist online to prevent snoopers/intercepters from seeing the sensitive data; this is not very costly, as these types of systems are common in production
  - **2FA/multisig**: a two-factor authentication scheme or multisignature confirmation couldc be implemented to prevent damage from leaked credentials; this is not very costly, and would hugely benefit the company => otherwise a single leak would compromise the entire credential tier
  - **private servers**: servers could be hosted in-house to prevent 3rd parties from viewing sensitive data; this is somewhat costly from a hardware perspective, and might be an unnecessary expense


## Problem 3
- Scenario: You are overseeing an election, and you are responsible for the security at voting centers.
- Assumptions:
  - each voter is only eligible with some proof of citizenship (credential)
  - each voter should only receive a single vote
  - votes must be transferred from voting centers to govt tallying centers
- Assets:
  - **voters**: the voters attending the voting centers should be protected from any physical danger/threats which could influence how they vote
  - **completed ballots**: the completed ballots with voter choices should be protected from tampering 
  - **transportation vehicles**: the vehicles used to transfer the completed ballots from the voting centers to govt tallying centers needs to be protected
- Threats:
  - **physical threats**: someone with weapons/physical force could threaten voters entering and exiting the voting booths forcing them to vote a certain way
  - **ballot tampering**: someone who intercepts the ballots before they are tallied could change votes and violate the integrity of the tally
  - **revotes**: someone could attempt to vote multiple times with the same credential (potentially at different voting locations)
  - **fake credentials**: someone could attempt to manufacture fake credentials which allow them to vote multiple times according to the rules of the vote
- Countermeasures:
  - **metal detectors**: these are a relatively low-cost option for one-time rent which would prevent physical weapons being taken into voting centers (high benefit)
  - **complex credential system**: credentials used to identify single voters should validate several factors which are hard to fake/manufacture (low cost, high benefit)
  - **vote history**: a history of who has voted in the vote, irrespective of voting center is necessary to prevent revotes (somewhat high cost, but extremely necessary)
  - **police escort**: as a somewhat high-cost option, a police escort could be used to bring the completed ballots to tallying centers (somewhat low benefit)
  - **strategic locations**: to minimize the distance between voting centers and tallying centers, voting centers could be chosen carefully to reduce the time in transit of the completed ballots (low cost, low benefit)

