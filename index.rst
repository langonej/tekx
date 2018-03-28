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
            <p>Join us in #_hackathon_nola_ext on Slack for questions, comments, and important announcements.</p>
            <p><a class="btn btn-secondary" href="slack://channel?id=C9YL09A23&amp;team=T0252CLM8" role="button">Join Channel &raquo;</a></p>
        </div>
        <div class="col-md-6">
            <h2>Awards and Prizes</h2>
            <p>In addition to being recognized in front of their peers, the top team per category will win a meet and greet with celebrity chef and personality Anthony Bourdain on Thursday, May 10th during .NEXT, plus a $2,500 cash prize plus a donation of $2,500 to the nonprofit organization of your choice. 

</p>
        </div>
    </div>
    <hr>

Getting Started
===============

.. note::

  Welcome to our inaugural hackathon!  In an effort to help deliver the maximum hackathon experience we have made some of our internal training available to each of you.  The content within this site is typically used to perform a lab.  **However, since we are preparing our infrastructure for the hackathon, the content provided is for educational purposes only.**  We do not have online labs for use at this time. 
  
The Hackathon will start prompty at 08:00am on Tuesday May 8th, 2018.  If possible, please handle your in-person registration on Monday afternoon before 6pm.

Beginning on Wednesday you will be provided with a customer challenge. Your goal is to build and propose a solution using Nutanix and optional 3rd party technologies. The **Optional Labs** provide step by step guides for additional technologies you may find useful for your proposed solution. Bonus points can be earned by incorporating additional technologies (Chef, Puppet, Jenkins, etc.) not covered in **Optional Labs**.

Each team has been provided a four node cluster running AHV and AOS 5.5.1. **Upon Electing a Team Lead and Consulting Your Team Coach Please Exam Your Cluster.** Each cluster has been pre-staged with the following:


**Credentials**
- **Cluster Username:** admin **Password:** techX2018!

**Networks**

- **Network information is located on your team spreadsheet** - https://drive.google.com/drive/folders/1-8vVrC7Ad9uFeWnY1LcaffQQEoD-Eris
- **Link-Local** Network - **DO NOT ENABLE IPAM**

**Images**

- **All required images are pre-loaded onto your team's cluster**

**Virtual Machines**

- **PC** VM - 10.21.XX.39 - Nutanix Prism Central 5.5.1
- **DC** VM - 10.21.XX.40 - ntnxlab.local Domain Controller
- **XD** VM - 10.21.XX.41 - Citrix XenDesktop 7.15 Delivery Controller/StoreFront/License Server
- **HYCU** VM - 10.21.XX.44 - Comtrade HYCU 2.0.0
- **X-Ray** VM - 10.21.XX.45 - Nutanix X-Ray 2.2

.. note::

  Due to resource limitations, many labs are designed to be completed as a group. The Overview section of each lab will indicate whether the lab should be completed once per group/cluster or if it can be performed individually. **Do Not Start Labs Before Electing a Team Lead and Consulting Your Team Coach**
