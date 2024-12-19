# PetChain
PetChain is a decentralised blockchain-based platform that redefines the standards of pet care and management. Leveraging the power of Resilient DB, PetChain offers secure and tamper-proof pet identification, seamless health record management, automated insurance claim processing, and hassle-free ownership transfer capabilities. Our innovative lost-and-found feature significantly increases the chances of reuniting lost pets with their families, filling a vital gap in the industry. PetChain empowers pet owners with unparalleled transparency, efficiency, and control, creating a holistic ecosystem that prioritises the well-being and protection of animal companions.

**Features-**

**1. Pet Registration**

**Account Creation:** Pet owners can create accounts by providing personal details and setting up login credentials. Verification is performed via email or phone.<br>
**Pet Registration Form:** Owners can register their pets with details and Pet profile will be created.<br>

**2. Lost and Found Service** 

**Mark as Lost:** Owners can update their pet’s status to “Lost” and provide additional details such as last known location and special notes.<br>
**Finder Actions:** Finders can access the pet’s profile by entering its unique ID or scanning a tag.<br>
**Secure Communication:** Finders can notify owners and optionally share the pet’s last known location via secure messaging.<br>
**Blockchain Logging:** Lost and found events are logged immutably on the blockchain.

**3. Health Record Management**

**Owner Updates:** Pet owners can upload health records such as vaccination details, allergies, and minor illnesses.<br>
**Veterinarian Access:** Authorized veterinarians can add medical diagnoses, prescriptions, and treatment plans to the pet’s profile.<br>
**Data Privacy:** Health records are visible only to owners and veterinarians.<br>

**4. Ownership Transfer**

**Initiate Transfer:** Allowing owners to initiate ownership transfer with a secure request, generating an approval token for validation of transfer.<br>
**Email Notification:** Notify the new owner via email with an approval link for secure transfer.<br>
**Approval Process:** Validate pet details and ownership hash from databases, ensuring secure transfer of pet details.<br>
**Hash Generation and Logging:** Generate a transfer hash, log the event in ResDB, and update MongoDB with new ownership details (new owner’s name, ID, email, and so on).Transfer Status is displayed for a smooth user experience.

**5. Insurance Claim Management**

**Link Existing Insurance:** Owners can link existing insurance policies to their pet’s profile by providing policy details through smart contract. <br>
**Submit Claims:** Pet owners can upload required documents for insurance claims, including vet bills and medical reports. <br>
**Smart Contract Pre-Approval:** Claims are pre-validated by smart contracts before submission to the insurance provider.<br>
**Claim Status Updates:** Owners are notified about claim status (approved/denied) directly on the platform.<br>

**Technology Stack**

**Frontend**
React.js , MaterialUI

**Backend**
Node.js, expressjs

**Database**
ResilientDB (Blockchain-based database), mongoDB

**Blockchain** 

Practical Byzantine Fault Tolerance (PBFT)  blockchain protocol for logging events and managing smart contracts
For more info check out this blog [PetChain](https://blog.resilientdb.com/2024/12/08/PetChain.html)
