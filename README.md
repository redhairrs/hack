<p align="center">
 
![WhatsApp Image 2023-06-02 at 11 27 56 AM](https://github.com/redhairrs/hack/assets/86844932/df66564a-16f0-48e9-8bd5-2c826c4de16e)        
        </p>
<h1 align="center">VERIFYBHARAT</h1>
<h3 align="center">Trusted Protocol For India's Documents<h3>
  

<div align="center">
  
 
  [![made-with-react](https://img.shields.io/badge/React-2.1.5-brightgreen.svg?style=for-the-badge)](https://github.com/facebook/create-react-app)
   [![](https://img.shields.io/badge/-Ethereum-lightgrey.svg?style=for-the-badge)](https://www.ethereum.org/)
    ![](https://img.shields.io/badge/Smart%20-Contract-lightgrey.svg?style=for-the-badge)
 ![](https://img.shields.io/github/forks/nikhildsahu/E-Certify.svg?style=for-the-badge) 
  ![](https://img.shields.io/github/stars/nikhildsahu/E-Certify.svg?style=for-the-badge) 
  ![](https://img.shields.io/github/license/nikhildsahu/E-Certify.svg?style=for-the-badge)
  
 </div>

##  E-Certify : About
- It is a blockchain based project for online certificate validation. 
- The major problem of counterfeit certificates can be tackled with the help of VERIFYBHARAT, as it provides a solution to preserve the genuineness of certificate. 
- It works on the idea that:
   - Utilizing blockchain technology to create an immutable and transparent ledger for certificate storage.
   - Provides a affordable solution with easy and efficient verification of documents.
   - Provides a secure and tamper-proof environment for storing and sharing certificates.
   - Allows individuals to grant controlled access to their certificates to authorized parties.
## Insight
- It is D-App on [Ethereum](https://www.ethereum.org/).
- Back-End has Smart Contract 
- Front-end of our Web-App is made with [React.Js](https://github.com/facebook/create-react-app) and our complete frontend components are available at 
      https://github.com/Abhin4vKumar/VerifyBharat
 <br>
<p align="center">
 ![image](https://github.com/redhairrs/hack/assets/86844932/b669d714-ff2f-4d64-9ff8-da0107d558da)
</p>

- It create Multi-Sig Wallets for every student where both Student and his/her Institute is Owner.
- We are using Browser Extension to work with Ethereum.
 <br>
  <p align="center">
    ![image](https://github.com/redhairrs/hack/assets/86844932/9dc12f8d-a354-49f2-8317-33be84c57e70)
 </p>

## How to Use

### Login
- There are two ways to login
  - Login as `Student`
  - Login as `Institute`
    ![image](https://github.com/redhairrs/hack/assets/86844932/45d28ad5-dab3-410b-be52-c206eb460845)
<p align="center">
    ![image](https://github.com/redhairrs/hack/assets/86844932/f850778e-efa7-4cc9-886f-d844c1df0ccc)
</p>

 - Upon First Signup `Metamask` will ask permission to connect your wallet with App.

### Dashboard

 #### Student Dashboard
 
  
 <p align="center">
   ![image](https://github.com/redhairrs/hack/assets/86844932/080e6a9b-920b-42f2-9a69-29853da3ff69)
</p>   
 
- Student Dashboard have these options :
 
 - `My Documents`
   - Students can upload their Certificates themselves but these certificates need to be verified by Institute side ,only then                 certificates will appear in my documents section.
 
 - `Give Access`
    - Students can give access to any other institute/organisation to his/her certificates , access is only given for limited time             (24hr)
 
 - `Change Institute` 
    - Students can request change of institute , this request is sent to current institute ,Upon approval students institute is changed. 
   
## Installation 

### For Development
 - We are using Truffle for testing and development of this project.
 - Also you need to have Metamask Browser Extension.
 - For setting up Truffle (more detailed instruction are avalaible [here](https://github.com/truffle-box/react-box) )  
 - Steps :
   - Clone the repo
   > $ git clone https://github.com/nikhildsahu/E-Certify.git
   - Setup Truffle
     - Install truffle
     > $ npm install -g truffle
     - Unbox React inside any Directory 
     > $ truffle unbox react
     - Inside that Directory
     - Now replace Contracts folder with  Contracts folder present in Repo.
     - Also Copy Complete Repo content in to Client folder. 
     - Run the development console 
     > $ truffle develop
     - Compile and migrate the smart contracts.
     > compile
     
     > migrate
     - In the client directory, we run the React app.
     >// in another terminal (i.e. not in the truffle develop prompt)
     
     > $ cd client
     
     > $ npm run start
     
  - Open http://localhost:3000 to view it in the browser.       
  - Import Account on Metamask with keys given by Truffle .
  - Testing and Development can be done on these Accounts.
  - Smart contract changes must be manually recompiled and migrated then only it will work.
  -------------------------------------
  ## Contributing
  - We're are open to enhancements & bug-fixes.
  - Feel free to add issues and submit patches.
  ## Authors
  - Atharva Udapure - [atharvau](https://github.com/atharvau)
  - Nikhil Sahu - [nikhildsahu](https://github.com/nikhildsahu)
  - Gaurav Sharma - [gauravsharma-gs](https://github.com/gauravsharma-gs)
## License
This project is licensed under the MIT - see the [LICENSE](https://github.com/nikhildsahu/E-Certify/blob/master/LICENSE) file for details.
