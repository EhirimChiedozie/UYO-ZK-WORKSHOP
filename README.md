#WORKSHOPS

  First Worksop:
    Transaction Id: at1tyzgphffz26xkpvyqyu7a8729zmlvntuxc94kxdsxqwzefjqugxs3lfeyt
  
  Second Workshop:
    Transaction Id: at1lhp4pmn7hpmpjd0rapp8j56kg92xanypjcdw0nrjsrdjadl0vygsjq0awu
  
  Third Workshop:
    Transaction Id: at152t7733awv83jgkwtfa4sp685vae04y4ap7s5e5hq4uc38kwyy8q2qde0g


    
#Description
  #First Workshop:
    open your git bash terminal and clone the repository using `git clone https://github.com/EhirimChiedozie/UYO-ZK-WORKSHOP`
    cd into the repository `cd UYO-ZK-WORKSHOP`
    then cd into the first workshop folder `cd chiedozieehirim`
    run the program `leo run main 3u32 5u32 --network testnet`
    this return 8u32 which is the sum of 3u32 and 5u32.
    To deploy, use `leo deploy`
    Note, before deployment go to the .env file and change the PRIVATE_KEY to your personal private key

  #Second Workshop
    After running the first program, cd into the root directory `cd ..`
    then cd into the folder of the second workshop `cd chiedozie_token`
    then run the program using `leo run mint <leo wallet id> 1000u64 --network testnet`
    You can deploy by using `leo deploy`. Remember  to cange the PRIVATE_KEY in your .env file to your personal private
    key.

#Third Workshop
  run `cd ..` to get into the root directory
  then run `cd mmaduakolam_blockchain` to cd into the third workshop folder.
  You can run the program using
  `leo run combine_hash_owner_receiver <your leo wallet address> <your friend's leo wallet address>`
  You can deploy by using `leo deploy`. Remember  to cange the PRIVATE_KEY in your .env file to your personal private
  key.
