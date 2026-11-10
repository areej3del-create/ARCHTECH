← → OR CLICK TO NAVIGATE · F FULLSCREEN

ELEVATION\
FRONT VIEW

FLAT ROOF\
CONCRETE STRUCTURE\
STEEL FRAME

SECTION A-A\
SCALE 1:100

4.80

17.60

Archi

T

E

C

H

DESIGN. PLAN. BUILD. **REAL FUTURES.**

AI-POWERED ARCHITECTURAL DESIGN PLATFORM

SE322\
ALJAWHARA ALRUZOUQ | AREEJ ALMARRI | GALA ALALULA | RUMAH JUWERIA

ArchiTECH

PROBLEMSTATEMENTS

Users struggle with home planning processes that require multiple unconnected tools and services.

Traditional 2D drawings make it difficult for users to realistically understand spatial layouts and design outcomes.

Many users experience stress and confusion during planning due to lack of guidance and difficulty visualizing ideas.

Existing tools often focus on visualization only and do not support full execution-oriented outcomes.

ArchiTECH

PROJECTOBJECTIVES

Integrate all necessary planning and design tools into one guided platform.

Make home planning an intuitive and user-friendly process.

Use AI to support users in generating design ideas and layouts.

Employ high-fidelity 3D modeling and VR walkthroughs to improve visualization.

Bridge users and architects within one collaborative digital ecosystem.

AI-generated layoutMORA / RCRC ✓Cost in SAR

0

FUNCTIONAL REQUIREMENTS

0

NONFUNCTIONAL REQUIREMENTS

ArchiTECH

CLIENT-SERVER ARCHITECTURE

### Clients

- Web app (React)
- Mobile app (React Native)
- VR viewer (WebXR)

### API Gateway

- Single entry point
- Login and role checks
- REST and WebSockets

### Services

- Account, Support
- Visualization
- AI Layout
- Compliance, Cost
- Collaboration
- Export, Notification

### Adapters

- AI Adapter
- Rules Adapter
- Storage Adapter
- Design Repository

### External

- AI Engine API
- MORA/RCRC Rules
- Object Storage
- MySQL Database
- Email/SMS Gateway

ArchiTECH

QUALITYATTRIBUTES

1\) Security

100% of unauthorized requests blocked; only people with permission can open a project, and all data is encrypted.

0%

2\) Performance

first layout in 10 seconds, even when many people are online

0SEC

3\) Availability

99.5% monthly uptime; if one server crashes, another takes over, so you lose almost no work

0%

4\) Usability

anyone can create their first layout within 10 minutes, with no architecture knowledge needed

0MIN

ArchiTECH

DESIGNPATTERNS

### ADAPTER

Structural

- **WHERE:** AI rules & storage adapters
- **WHY:** Swap AI/rules provider without changing services

### STRATEGY

Behavioral

- **WHERE:** Cost rules, MORA vs RCRC rule sets, export formats
- **WHY:** Swap algorithms: template fallback if AI times out

### OBSERVER

Behavioral

- **WHERE:** Comments, votes, annotations, notifications
- **WHY:** One change updates every viewer live

### MEMENTO

Behavioral

- **WHERE:** Design versions, last 10 kept
- **WHY:** Auto-save and restore of design versions

ArchiTECH

VALIDATION &RESULTS

### Requirements coverage

- Checked that every requirement in the SRS has a matching design decision
- **RESULT:** 31 of 38 FRs and 16 of 18 NFRs fully covered

0/38FRS

0/18NFRS

### Consistency across phases

- Compared names, services, technologies and diagrams across phases 1 to 3
- **RESULT:** Documents now agree, and the mismatches were fixed

PHASE 1✓

→

PHASE 2✓

→

PHASE 3✓

### Quality scenarios

- Walked each quality attribute through the design
- **RESULT:** Each scenario is met by a specific component or pattern

SECURITYAPI GATEWAY✓

PERFORMANCESTRATEGY✓

AVAILABILITYMEMENTO✓

USABILITYOBSERVER✓

ArchiTECH

CONCLUSION

PHASE 1 · SRS AND SAD

We defined what ArchiTech must do in 38 functional and 18 nonfunctional requirements, and described its architecture with the 4+1 view model.

PHASE 2 · ARCHITECTURE

We chose four quality attributes, security, performance, availability and usability, and the Client-Server style that supports them.

PHASE 3 · SOFTWARE DESIGN

We applied Adapter, Strategy, Observer and Memento, and traced each pattern back to a quality attribute and the SRS requirements.

From requirements, to architecture, to design:every design decision traces back to a requirement.

ArchiTECH

PROTOTYPE DEMO

CLICK TO PLAY

THANK YOU

ArchiTECH

01 / 09