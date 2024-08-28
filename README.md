# Pryde-Of-Web3_ZkWorkshop
![Screenshot_20240828-065253](https://github.com/user-attachments/assets/c9c19046-118d-4892-91f0-4a22feb698b2)
*Workshop 1*

- Transaction ID: at1pyv2qkv60fn2dd2zxpuy52z3ustj8mdtyasp7u23hrqa8u205qgqyqtxwj
- Command: `leo run main 3u32 2u32 --network testnet`
    - Where:
        - `main` is the transition function name
        - `3u32 2u32` are the inputs
        - `--network testnet` specifies the network
- Note: Deploy using `demo.leo.app` generated private key in `my.env`. Replace with your Leo wallet private key to avoid errors.

*Workshop 2*

- Transaction ID: at19w6t8am5wjflhlmgrgmsdvaw4j7vr2rky4k6ycpmeuf4tfs065zs3ufjzd
- Commands:
    1. `leo run mint <type_aleo_address> <type_amount>u64`
        - Record generated from simple token (build and src files) copied to my token file for successful deployment.
        - Replace generated private key in `my.env` with your Leo wallet private key.
    2. `leo run transfer "<Token_Record>" <to_address> <amount>u64`
        - Use generated record from 1st command as input for 2nd command.
        - Replace generated private key in `my.env` with your Leo wallet private key.

*Workshop 3*

- Transaction ID: at1hetxvcc6xvfskyw2vrsrhwe4nqjymucrchdz3fgtgr6hxgsnpcpqcrgfql
- Command: `leo run combine_hash_owner_receiver <type_your_address> <type_friend_address>`
    - Inputs:
        - Owner address (self.caller)
        - Receiver address
- Note: Replace generated private key in `my.env` with your Leo wallet private key to avoid errors.

*Signature*

`sign15tn82dtnsysl2679x05ts63jk2f4tny8ucvdsnn6x7t3ycq3xgq2vcee7an4dy2z9xl97nesdd3t9nrzztpw425wzlwu4pz07mrlqqjdq7eslqkgfdr5x892mpwvrzjhk754tpsx3rtkkssavwd283p2pexn5acn3de2ncynu7m3jyuwhv8javw73tkg6vtf67htgwdln27qzca9sqq
