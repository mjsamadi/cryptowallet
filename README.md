## Cryptocurrency Wallet

![An image shows a wallet with bitcoin.](Images/19-4-challenge-image.png)

---

## Background

You work at a startup that is building a new and disruptive platform called KryptoJobs2Go. KryptoJobs2Go is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As KryptoJobs2Go’s lead developer, you have been tasked with integrating the Ethereum blockchain network into the application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

In this Challenge, you will complete the code that enables your customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, you will assume the perspective of a KryptoJobs2Go customer who is using the application to find a fintech professional and pay them for their work.

### Step 1, Part 3- Import functions from the `crypto_wallet.py` file:

    from crypto_wallet import generate_account, get_balance, send_transaction

### Step 1, Part 4: Create a variable named `account`:

    account = generate_account()

### Step 1, Part 5: Get Balance:

    ether_balance = get_balance(w3, account.address)
    st.sidebar.write("4th Account Balance:",ether_balance)

### Step 2, Part 1: Wage Calculation:

    wage= candidate_database[person][3]* hours
    st.sidebar.write("Wage:", wage)

### Step 2, Part 2: Send Transaction:

    transaction_hash = send_transaction(w3, account, candidate_address, wage)

---
## Inspect the Transaction

1. Run Application (Main Menu)
![alt=""](Images/1.png)

2. Select and set hours
![alt=""](Images/4.png)

3. Ganash before transaction
![alt=""](Images/3.png)

4. Send transaction 
![alt=""](Images/2.png)

5. Ganash after transaction 
![alt=""](Images/6.png)

6. Transaction detail in Ganash 
![alt=""](Images/7.png)


## Files:
1. [Crypto Wallet](crypto_wallet.py)
2. [Crypto Job](krypto_jobs.py)

