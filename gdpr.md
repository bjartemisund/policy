---
title: Whereby's GDPR Statement
description: Whereby's GDPR statement
slug: /information/gdpr/
---

# Whereby's GDPR Statement

This page provides information about the initiatives we have taken to be compliant with GDPR. We want to help you, our customers, understand our commitment to upholding the privacy and security of your data better so you can make an informed decision before using our services.

## Background

The General Data Protection Regulation (GDPR) is a piece of legislation that is designed to strengthen and unify data protection laws for all individuals within the European Union(EU) and European Economic Area (EEA).

## Whereby's GDPR commitments

Since its inception, Whereby’s approach has been anchored with a strong commitment to privacy, security and transparency. This approach includes upholding the privacy and security of our individual customers' data as well as supporting our Embedded customers to demonstrate their compliance with data protection requirements set out in GDPR.

We provide contractual commitments to our customers regarding our compliance with applicable EU data protection law. This guarantees that:

* We only process personal data as identified in our [Privacy Policy](/information/tos/privacy-policy/) in order to deliver our services
* We carry out a thorough assessment before adding any sub-processors and only add those who meet our data protection standards
* We implement technical and organizational measures, that are based on industry best practices, to secure the data of our customers as outlined in our [Data Processing Agreement](/information/dpa/) (DPA)
* We assist customers in exercising their rights pertaining to data we process for providing our service (such as right to information, access, rectification, data portability and deletion).

We continue to monitor any legal developments and guidance around GDPR from regulatory bodies and update our existing policies and agreements regularly. We will update you of any changes in our obligations so that you are always up-to-date.


## GDPR-friendly features in Whereby

* Communication data (audio, video, screen sharing, chat and other content)

Whereby operates a global infrastructure of video routers distributed across the world, and users will be automatically routed to the closest available one to them. IP addresses will only be used to connect the user with a data center in their region. This means that users in European countries will connect to a data center physically located within the EEC. The video router servers and all of Whereby’s infrastructure adhere to strict security measures, preventing malicious eavesdropping or interruption of the video/audio streams.

Media sent between participants in a room will not be stored. Hosting providers used to route video calls do not have the ability to access or control the data streams, nor is any transmission initiated by them. Data sent through Whereby is initiated by the customer, the customer selects the receiver of the transmission and neither Whereby nor its subcontractors are able to select or modify the information contained in the transmission. Whereby will act as the controller, c.f Article 4(7) GDPR, for call data. Whereby is otherwise the processor, c.f Article 4(8), and the processing will be governed by the [Privacy Policy](/information/tos/privacy-policy/).

* End-to-end encryption

Whereby’s system is designed to comply with European privacy regulations (such as GDPR) and as long as it is recognized that the IP connecting to the TURN server is located in Europe, the user is guaranteed to connect to a server in the EEA. Data centers are dedicated for traffic in those regions and will only be used if a participant is located within one of those countries/regions. Data is always encrypted as it passes through the data processor’s servers; the hosting providers used do not have the theoretical opportunity to intercept the traffic.

Users can choose between “Small” room size (up to 4 participants) and larger rooms. In “Small” room size, communication between participants are primarily sent through peer-to-peer connections, where audio and video streams are sent directly between participants and do not pass through any of our servers in cases where this is allowed by the network the user is on. Video and audio transmitted in the Service are then sent directly between the participants in a room and are encrypted (DTLS-SRTP) with user-generated encryption keys. In cases where a user is behind a strict firewall or NAT (e.g. on a strict corporate network), video and audio need to be relayed via a TURN server, but end-to-end encryption is still maintained.

Calls using a larger room size will use a dedicated server infrastructure to allow more people to join the room and get better stability. The video stream in larger rooms will be sent through video router servers which transmits it to the other participants in the call, and also transmit their streams to the organizer. Streams will always be encrypted (DTLS-SRTP) in transit but will be decrypted and re-encrypted when passing through the video routers.

* Encryption in Transit

Besides end-to-end encryption described above (which is relevant for audio and video streams within the platform), Whereby relies on encryption-in-transit for the communication between end users and their account administration, for communication between infrastructure components and for communication. This is facilitated by the HTTPS and TLS 1.2 protocols. Any  protocols previous to TLS 1.2 are strictly forbidden.

* Strong authentication

If users are relying on email authentication or Single Sign on, they will receive a one-time-code in their mailbox.The one-time-code is not known by anybody at Whereby and it is randomly generated at the moment of the authentication request being sent. If users rely on Single Sign On, they will authenticate against the identity provider that they were already relying on (e.g Apple, Google). Therefore, it removes the need for end users to rely on passwords and removes the need for Whereby to store and process passwords, which greatly minimizes the risk of unauthorized user access if the Whereby databases are compromised.

* Call recording

The "Recording" add-on feature, which is available in the Pro and Business plans, only allows user-side recording, so the recording is never uploaded to Whereby’s servers. The user who starts the recording (the user must be a host in order to do this) is responsible for getting consent from all participants prior to starting the recording. They are also responsible for storing and processing the recording in compliance with regulations after downloading it from Whereby.

* Chat messages

Chat messages are not stored permanently. In order to pass the messages to each participant in the call, the messages pass through Whereby's servers temporarily. However, all of the messages are deleted from the server as soon as it has been delivered to the participant's device.  Additionally, as each participant leaves the room, the chat messages that were stored locally on their computer are deleted. Customers using the video meetings API will have the option to disable chat entirely.

* Dashboard

Users with accounts, of both Meetings and Embedded plans, have the ability to see their data straight from their dashboard and download exactly what our database has stored about them. Under the Privacy section in the dashboard, users can change their consent and opt in or out of communication they’d like to receive from Whereby. Read more here [Profile & Data Management](https://whereby.helpscoutdocs.com/article/533-profile-data-management)

* Minimal data collection

Whereby keeps very minimal data on its users. Users have the ability to use Whereby anonymously without providing an email address or downloading anything to join a meeting. If a user decides to create an account with Whereby the only information it stores for that user is what is strictly necessary for creating the account; email address and pictures they upload in our paid plans for their profile or background pictures for their rooms.  As mentioned before, no video conversations or chat conversations are stored on Whereby's servers. For plans that use recording, this is done completely at the local level and not stored with Whereby.

## Contact us
If you have any questions or concerns or would like to give us feedback, please contact privacy@whereby.com or DPO@whereby.com
