
<div align="center">
    
# Decentralized Hiring/ Freelance Platform
    
##### Created by [Demi Oyebanji](mailto:oluwademiladeoyebanji@outlook.com) as an assignment for the **UofT SCS Financial Technology Bootcamp**
________________________________________________________________________________________________________

</div>


**Imported Function From Crypto_Wallet**

![Import Functions](Resources/ImpFuncsfromcry.png)

**Created 'Generate Account' Function in Streamlit front-end**

![Generate Account](Resources/SidebrGenAcc.png)

**Created 'Wage' Calculators in Streamlit front-end**

![Generate Account](Resources/SidebrWage.png)

**Created 'Send Transaction' Function in Streamlit front-end**

![Generate Account](Resources/Sidebr_SendTrans.png)


#### Kept recieving errors so had to make some further changes to the code

**Tested different methods of generating the private key but at the end the from_key method was the only thing that worked**

![Generate Account Fixes](Resources/generate_account_fixes.png)

**Also had to change a lot of functions either from or to an older version. Things like changing ToWei to to_wei and so on**

![Other Function Fixes](Resources/function_fixes_other.png)

### The generated front-end in Streamlit
![StreamlitPage](Resources/streamlitpage.png)

### I was able to fill out the transaction information but I kept running into more errors
![Attemptiung to Send Transaction](Resources/Sendtranattempt1.png)



### To fix the errors, I had to store my private key as an additional variable from the environment. If I didn't do this the account key info would save as a string. 

![Isolating Private/ Public Keys](Resources/Isolatekey.png)

### This alllowed me to insert the private key directly into the signature and sign the transactions. 
![Adding the new Private Key variable into the signature line](Resources/KeyInsert.png)

### Which allowed me to finally run the transaction and recieve the transaction hash

![Attemptiung to Send Transaction](Resources/Sendtranattempt2.png)
![Attemptiung to Send Transaction](Resources/Sendtranattempt3.png)
