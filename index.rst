.. title:: .Next Hackathon 2018 New Orleans

.. _intro-docs:

.. toctree::
  :maxdepth: 2
  :caption:     Suggested Reading
  :name: _req-labs
  :hidden:

  .. example/index
  ssp/ssp
  calm_mysql/calm_mysql
  calm_lamp/calm_lamp
  calm_mrkt_p1/calm_marketplace_p1
  calm_mrkt_p2/calm_marketplace_p2
  github/github

.. toctree::
  :maxdepth: 2
  :caption:     Optional Reading
  :name: _opt-labs
  :hidden:

  afs/index
  git/gitlab
  docker/calm_workshop_lab7_docker
  .. k8s/index
  ansible/calm_workshop_lab6
  rest/calm/calm_workshop_lab5_api
  .. terraform/index

.. toctree::
  :maxdepth: 2
  :caption:     Other Resources
  :name: _resources
  :hidden:

  .. jenkins/index
  .. chef/index
  .. puppet/index

.. raw:: html

    <div class="row">
        <div class="col-md-6">
            <h2>Need Support?</h2>
            <p>Please reach out to your team's Nutanix mentor.</p>
        </div>
        <div class="col-md-6">
            <h2>Teams</h2>
            <p>Team rosters are below; team members in ALL CAPS are a dedicated Nutanix team mentor</p>
            ** OFFICIAL ROSTERS BELOW **  
            See an error? Please contact Jason (jason@nutanix.com)

- **Ctrl Alt Elite** Michael Lowry, Jayesh Mankodi, Mustafa Ahmed Syed, James Quigley, MARCEL MESSIN

- **BLUE** Bryan Kuhn, Tom Carter, Ryan Admire, Michael Eberhard, ANDY SCHMID

- **COPPER** Jeremy Francis, John Freeman, David LeClair, PRATAP TIWARY

- **CYANTIX**  Stephen Baker, Reed Beaver, Samuel Hanke, James Johnson, MICHAEL WOLFE 

- **Virtually Amazing**  Matt Rice, Marlon Wenceslao, Christopher Williams, Joel Winkelmann, RIK FAITH

- **GRAY** Brian Jayes, Jeremy Nicolaisen, Rocky Reyes, PJ Romero, BRENNAN CONLEY

- **GREEN** Jeremy Ayers, Kevin DeNiese, Mark Harden, Curtis Patterson, CONSTANTINE KOUSOLIS

- **LIME** Luis Carrillo, Michael Culmone, Jesse Jones, Jon Walton, AASHARAY ARORA

- **Did It All For The Cookies** Benjamin Craft, Chadd Dorr, Joseph Itson, Faisal Jawaid, RYAN HARDIN

- **Another Brick in the Firewall** Christopher Ermis, Byron Gandy, Grant Strang, Gus Thompson, DAVE KEEFE

- **PURPLE** Jonathan Kronimus, Aldwin Leon, Eric Miller, Matthew Pettigrove, KIRAN TATIPARTHI

- **RED** Kevin Hanser, Edward Lam, Todd Madsen, Christopher Tilley, JOSH SINCLAIR

- **TANGERINE** Corey Brookshire, Heather Danielson, Doug Fabec, Keith Lea, PRATEEK KAJARIA

- **Prometheus** Sean Bollinger, Donnie Lee, Steven Pearson, Jonathan Reich, JOSEPH MALEY

- **YELLOW** Raymond Lin, Juan Rojas, Wilson Silva dos Santos, Aliaksei Tryputsen, MICHAEL JASTAD (MJ)
        </div>
<div class="row">
Getting Started
===============

.. note::

  Welcome to our inaugural hackathon!  In an effort to help deliver the maximum hackathon experience we have made some of our internal training available to each of you.  The content within this site is typically used to perform a lab.  **However, since we are preparing our infrastructure for the hackathon, the content provided is for educational purposes only.**  We do not have online labs for use at this time. 
  
The Challenges
===============
As this is our first ever .Next Hackathon our goal is to ensure we provide maximum fun and also an environment of maximum creativity.  Your team will be asked to build a solution during the allotted window on Tuesday May 8th.  We kindly ask that you do not pre-build your solutions ahead of time.  Research, tinkering with new platforms, iterating your ideas, however, is absolutely encouraged!

Your team's submission will be evaluated by a panel of judges and the winner will be announced during a special time slot during the main .Next Conference!

Your team's submission must adhere to *one of the categories below*.

- *LIVE*
Showcase how interacting with the Nutanix Enterprise Cloud OS can be woven into one's everyday life.

CHALLENGE
In this challenge, we are looking for new ways to manage or interface with Nutanix Enterprise Cloud OS! Push our APIs and integrate it with everyday platforms such as Alexa, home automation platforms, or external APIs. Ideas include deploying new workloads with Google Home or failing over your environment from your smart watch.

- *WORK*
Showcase how the Nutanix Enterprise Cloud OS can make the workday easier.

CHALLENGE
In this challenge, we want to see who can create the most elegant answer to automate application-either one of your own choosing or one of the many Nutanix partner workloads! Ideas include automating the setup of remote site when it powers up and deploying the required network services or creating a super-health check that combines NCC, a DR recovery check and even a DB integrity check? What task will you automate?

- *PLAY*
Showcase an entertaining solution for next-generation IT that utilizes the Nutanix Enterprise Cloud OS.

CHALLENGE
Creativity is king! How can we integrate bleeding-edge IT into Nutanix? Take a stateful application and turn it into a distributed Kubernetes pod or create a blockchain-based budgeting method to deploy or share resources or even use sizing insights to convert a VM to a Kubernetes container running on Google Cloud Platform. We want to see your creativity!
 
Logistics
===============
  
The Hackathon will start prompty at 08:00am on Tuesday May 8th, 2018.  Main .Next Conference registration will begin at 0700 on Tuesday.  Please head to registration and you will be guided to the special area for the Hackathon.

Hackathon Breakfast will start at 0730.

Beginning on Wednesday May 2nd, 2018, each team will have full access to their own cluster.  Details on how to connect, credentials, and other useful info, will be posted directly to this site.

The Hacking Environment
===============
This hackathon will utilize hosted Nutanix clusters.  Connectivity will likely be provided through a virtual desktop session with dedicated bandwidth.

*What does this mean?*

This means that there will be no direct network access to the cluster.  You will be developing your solution in the hosted environment.

*Suggested Things to Consider*

Nutanix Calm for building blue prints may be a powerful tool in the solution.  Your team will be free to build and deploy containers and VMs so external solutions could be built and deployed (eg Node-RED, MagicMirror).

Hosted Cluster Info (will be updated)
===============


Each cluster has been pre-staged with the following (placeholder info for now):


**Credentials**
- **Cluster Username:** admin **Password:** xxxxx

**Networks**

- **Network information is located on your team spreadsheet** - <google drive link>
- **Link-Local** Network - **DO NOT ENABLE IPAM**

**Images**

- **All required images are pre-loaded onto your team's cluster**

**Virtual Machines**

- **PC** VM - 10.21.XX.39 - Nutanix Prism Central 5.5.1
- **DC** VM - 10.21.XX.40 - ntnxlab.local Domain Controller
- **XD** VM - 10.21.XX.41 - Citrix XenDesktop 7.15 Delivery Controller/StoreFront/License Server
- **HYCU** VM - 10.21.XX.44 - Comtrade HYCU 2.0.0

.. note::
        
