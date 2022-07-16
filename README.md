# Simamisa_Angular
Angular code for the Simamisa website

## Introduction
In the world we live in today, we often find ourselves overwhelmed by everything that happens. From the war in Ukraine and thousands of malnourished children in Tigran to keeping our own lives in perfect order. In what now seems like the aftermath of the covid-19 pandemic most NGOs lost funding and received fewer donations as companies closed down and major job cuts were experienced. To have a wider reach, an online presence has become imperative for such organizations. We i.e. The Bit-Reapers, want to help orphanages achieve this goal. Utilizing technology to help users have a net positive impact in the world. Our application does this by making it easier to assist the needs of orphanages. These needs range from fundraising to the need for volunteers.

## Industry background
 There are more than 3 million orphans in South Africa, orphanages saw a sharp increase in the numbers as COVID left more than 1.4 million children without parents/guardians. Orphanages often struggle to come up with the funds to meet the needs of the children they cater for, which has led the government to impose a rule that all orphanages should not depend on donors or sponsors in order to operate, but even this is troublesome for them. It is extremely difficult to get sponsors that are consistent, a lot of them are seasonal and aim to help meet one specific need. The situation has worsened since the pandemic as the people/companies who were sponsoring the homes ran out of funds, ran out of business and some passed on. A lot of orphanages are barely making it to the end of the month as their children are in need of food, clothes, stationery, medication, the list goes on. 

We approached an orphanage in Atteridgeville Pretoria called Kingdom Life Children Centre. It was started in 1999 by Mrs. Magoba, her home, providing shelter and love for three children. Today they have moved into a new property accommodating at least 40 children. Mrs. Magoba identified a municipality abandoned clinic and with the little she had, cleaned up the property. Many children living in desperate situations have no home, being neglected, physically, sexually, and emotionally abused, orphaned children now have a place they can call home. 

## Current systems and procedures followed
The orphanage currently has 13 staff members. The founder also has a husband who plays the role of a father figure to the children. Kingdom life caters to 50 children currently, their only consistent sponsors are Woolworths and PicknPay. They have to hope and pray that there will be additional sponsors that will meet their needs if such sponsors arise. Although the centre is registered to accommodate a maximum of 38 children, ages 4 to 18 years, they often have to accommodate more children, even those under and over the allowed group. They find it hard to meet the children's needs and keep up the costs of running the orphanage. They generate an income by running a church on the premises, they also rent out their sound system and have their musical services out for hire (singers, pianists, drummists, etc.). They have found it very difficult to keep track of the people that sponsor them and struggle with letting them know what they are in need of, they resort to sending emails and reaching out on social media which takes weeks and sometimes months to get responses. They have difficulty reaching out to volunteers and have to manually keep track of them via pen and paper when they eventually come to offer their services.

## Problem Statement
Orphanages need to reach out to a wider pool of potential sponsors and often the donations that the orphanage gets do not cover their actual needs. They are required to have a fundraising program and not solely depend on donations. Orphanages would also like people to know that they are there to help children and anyone who has knowledge of children in need should reach out to them.  There is a need to allow sponsors to have more interactions with the children they are sponsoring and to cater to different kinds of charitable acts.

## Proposed Solution
For a better relationship between orphanages and sponsors, a more constructive
system is required.
The users in our system are as follows:
1. Chile - A child from a specific orphanage.
2. Sponsor - Someone who is interested in assisting the orphanage with its needs
3. Volunteer - Someone who would like to assist the orphanage with small tasks.
4. Admin - The person in charge of the orphanage's management. 

In our system, they are monitoring communication between sponsors and children, as
well as publishing events.
Our system is designed to make it as simple as possible for sponsors to donate,
sponsor a child, and visit the orphanage.The sponsor will be able to log into our
system and review the needs of various orphanages that are presented to them, before
deciding which ones they want to support. The Sponsor will be able to request to
sponsor an orphan at a specific orphanage, and the administrator will have to walk them
through a process before approving or rejecting their request. When the sponsor's
request of sponsoring a child is approved, the sponsor will be able to communicate
with the child directly within our system, and the admin will be monitoring the
child-sponsor interaction at all times.
The child and the administrator are responsible for posting their needs on our
system's social feed feature so that the sponsor can see them. However, anything
posted by the child must first be approved or disapproved by the administrator before
being made public.
Our system also takes into account the fact that people are constantly looking for
orphanages to volunteer at but are having difficulty finding them. To assist with this, our
system allows these individuals to simply create a volunteer account on our system,
where they will be able to view volunteer opportunities as well as events that they may
be interested in attending at that orphanage.
To assist orphanages in generating a source of income so that they can become
self-sufficient.Our system aspires to form a relationship with yaga marketplace, through
which the orphanage will be able to sell items. This is due to the fact that orphanages
occasionally receive excess items as a form donation and are unsure what to do with
them.Rather than keeping these items, we encourage the orphanage to trade them in
order to generate some income.

# Requirements Extraction
## Functional Requirements

**Every user must be able to perform the following:**
* Register an account.
* Login into their account.
* Change their password if they forget it.
* Make changes to their account information.
* View Orphanage Events.
* Visit orphanage's online charity store.
* Remove their account.

**A child must be able to perform the following:**
* Communicate with the sponsor
* Make a social feed post (particularly about their orphanage's needs).

**A sponsor must be able to perform the following:**
* Sponsor a child.
* Communicate with a child.
* Propose holding an event at an orphanage.

**A registered user must be able to perform the following:**
* View orphanage upcoming events.
* Receive updates on volunteering opportunities at the orphanage.

**An admin must be able to perform the following:**
* Approve or disapprove the child's posts on the social feed.
* Permit the sponsor to communicate with the child.
* Monitor the conversation between the sponsor and the child.
* Make a social feed post.
* Publish an orphanage event.
* Delete a user's account

## Non-Functional Requirements

* Availability: The system has to be up and running at all times as Kingdom Life has people for all over the world of different timezones who love to interact with them and help out where possible, the system must therefore be available 24 hours in a day.

* Usability: the system need to be attractive but also easy to use as a lot of people who are interested in helping orphanages are between the ages 45-75 and most of them are not familiar with technology. It also needs to be easy for the children to use and interact with because a lot of them do not have a strong tech background.

* Performance: The system needs to be at  optimal performance because it will be used as a medium of communication between sponsors/volunteers and the orphanage. A request for a certain service/ items needs to be delivered to the sponsors/volunteers with as little delay as possible, while handling other requests.

* Security: Even though the names and pictures of the children will not be stored on the system, the children will use the system as a medium of communication between them and their sponsor. In the case that the child chooses to share personal aspects of their life, only the admin who will facilitate communication, the sponsor and that particular child should be able to see that information. Therefore, user authentication, password management, authorization and role management must be observed.

* Compatibility: Our system should be compatible with all sorts of devices ad operating systems as the sponsors/volunteers offering their help will be from all parts of the world.

* Capacity: Our system should be able to store a lot of data as they will keep track of the children, the employees, the sponsors, the messages sent between different users, the inventory of what they currently have in stock to sell/give away to other orphanages.

* Maintainability: The orphanage will not be able to keep using the system if it requires constant fixing as they do not have the funds to pay developers. The system needs to be durable and maintainable
