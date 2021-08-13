# Joint Saving Account with Solidity 
I built a smart contract that automates financial processes and features, such as hosting joint savings accounts.

To automate the creation of joint savings accounts, I created a Solidity smart contract that accepts two user adresses. These addresses are able to control a joint savings account. This smart contract uses ether management functions to implement the financial requirements necessary for providing the features of a joint savings account. These features consist of the ability to deposit and withdraw funds from the account.

## Technologies

``` Solidity```

## Installation Guide
In order to open and run this program you have to follow these steps:

* Go to my repository in GitHub and open the repository called ```joint_saving_account_with_solidity_20```

* Copy the repository's link.

* Open Git Bash in your computer 

* Clone the repository by typing ```git clone``` and paste the link ```git@github.com:nestor39/joint_saving_account_with_solidity_20.git```.

* type ```start .``` from Git Bash and you are going to be able to see the file inside the folder that you downloaded onto your computer.

Open [Remix IDE website](https://remix.ethereum.org/#optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.4+commit.c7e474f2.js) , load the file onto the current workspace, compile and deploy the file.



### Usage

#### Testing the smart contract
Complie the smart contract without errors

![image](https://user-images.githubusercontent.com/80844686/129427138-4b53cf4d-3044-42b4-95dd-94dc4bb863cd.png)


Deploy your smart contract in the JavaScript VM

![deploy](https://user-images.githubusercontent.com/80844686/129427093-35c6acdd-0034-4c74-9341-3c31a83a577f.png)




#### Test ```deposit``` function

Use ```setAccount``` function

![image](https://user-images.githubusercontent.com/80844686/129427551-a8b0caa8-8137-420e-9b96-32655d1eab99.png)


Transaction 1: Send 1 ether as wei

![first_transaction](https://user-images.githubusercontent.com/80844686/129427326-4e413a99-95f2-4536-b712-766537b0b85b.png)


Transaction 2: Send 10 ether as wei

![second_transaction](https://user-images.githubusercontent.com/80844686/129427328-d217fdf7-47a0-41d2-8234-f7b65625d477.png)


Transaction 3: Send 5 ether

![third_transaction](https://user-images.githubusercontent.com/80844686/129427331-68058503-7723-4733-a7f2-8fcb43256210.png)


#### Test the withdrawal funcionality of the smart contract. Capture a screenshot of the two executions.

Withdraw 5 ether

![image](https://user-images.githubusercontent.com/80844686/129427708-3d64b53e-d824-4671-9970-0d3ddde6a0e9.png)

Withdraw 10 ether

![image](https://user-images.githubusercontent.com/80844686/129427751-1ea5b912-3957-489d-801e-365122b9affa.png)


## Contributors
Brought to you by Nestor Ramirez Cuadro

## License
[MIT](https://github.com/nestor39/joint_saving_account_with_solidity_20/blob/main/LICENSE)
