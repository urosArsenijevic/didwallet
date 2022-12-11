What is D-ID?

D-ID is a bitcoin wallet that allows the user to prove his identity online and represents a direct replacement to an identification document such as an ID card or passport.

The entire process of registration, KYC verification and final user identification is completely digital and does not require live identification of the user, unlike current solutions on the market.



How it works?

D-ID connects an identification document such as a passport or ID card with the user's digital identity so that each potential user, in order to obtain the right to own a D-ID wallet, must first successfully become fully verified D-ID user, by completing 4 steps: registration, KYC check, identification, and wallet creation.

Possession of a D-ID wallet is proof that the user has previously passed all three steps, and that by possessing a D-ID wallet, he can provide proof of identity for inspection.

Registration - user enters email and password

KYC check - partnered up with Blinking.id - due diligence procedure of checking the client. The user also automatically receives the risk level in backoffice admin:
the user enters his data
through the Blinking SDK, the user takes a photo of his/her identity document and a selfie
we send data to Blinking for KYC verification using Optical Character Recognition (checking protective elements such as the validity of holograms, optically changing colors, embossed elements in order to reduce the risk of forgery or unauthorized changes) and Facial Recognition (liveness check and recording users face in order to compare it with personal ID image)

we get one of three statuses:
VERIFIED - the user has successfully passed the KYC check
PROCESSING - additional time is required to process the user's file and possibly additional documentation will be needed
REJECTED - the user has not passed the KYC check and unfortunately cannot create a DID wallet

Identification- partnered up with Blinking.id - user identification is done via video call with one of our Custom Support agent. Blinking SDK enables recording of the entire procedure with high quality image and sound transmission and timestamping functionality, i.e. time marking with connection to the exact time source. The video transmission module relies on the WebRTC standard that enables real-time audio-video communication with each session encrypted.


Wallet creation - when the user is verified, a D-ID wallet is automatically created, thereby directly connecting the user's ID to the blockchain wallet since it is automatically created after the user has passed KYC verification and video identification among other process steps.



How does a user prove their digital identity?

Providing proof of identity without disclosing sensitive information is possible with the Zero knowledge proof concept.
The user provides his public key when registering an account on the third-party service he wants to use. When a third-party service wants to confirm the user's identity, it will encrypt a message by using the user's public key. Encrypted message can only be decrypted by User’s private key. The user then returns the originally encrypted word to the third-party service and, if the word is validated, confirms his identity.

