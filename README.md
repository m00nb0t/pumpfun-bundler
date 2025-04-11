##     ##  #######   #######  ##    ##     ########   #######  ######## 
###   ### ##     ## ##     ## ###   ##     ##     ## ##     ##    ##    
#### #### ##     ## ##     ## ####  ##     ##     ## ##     ##    ##    
## ### ## ##     ## ##     ## ## ## ##     ########  ##     ##    ##    
##     ## ##     ## ##     ## ##  ####     ##     ## ##     ##    ##    
##     ## ##     ## ##     ## ##   ### ### ##     ## ##     ##    ##    
##     ##  #######   #######  ##    ## ### ########   #######     ##    

(https://t.me/m00nb0t)

FULL PUMPFUN SUITE

✔️ Bundled Launch
Launch with up to 20 sidewallet buys (soon 28). If correctly warmed up, passes tradingbot bundle detection. NO private node, or lil jit support needed. Guaranteed atomic block zero for all your buys.

✔️ Delayed Launch
Launch organically, dump on snipers, and bundle buy with sidewallets. Even less tradingbot detection for your bundle.

✔️ Airdrop Launch
Instant airdrop for perfect distribution from launchwallet via proxy. If warmed up correctly, passes tradingbot bundle/insider detection.

✔️ Volume Bot
Multiple modes for generating authentic volume for your project, mev protected, configurable delays, buy amounts, supports infinite wallets in theory.

✔️ Bump Bot
Simple buy/sell mode for your projects visibility.

✔️ Profile Generation
Instant and configurable profile generation for your sidewallets on Pumpfun.

✔️ Custom Vanity CA's
Grinder for authentic "pump" vanity adresses, or any adress suffix / prefix that you want.

✔️ Warmup Mode
Smart auto warmup mode for your side wallets to evade flags from tradingbots and trackers.

✔️ JITO Sell All
Bundle sell on either pumpfun or pumpswap directly from the bot, fully atomic.

✔️ Pumpswap Support
All buy, sell and auto volume modes supported on pumpswap.

✔️ No Expensive RPC Needed
Our suite works directly with jito noauth endpoints. You DO NOT need an rpc or private node with Jito support. It is optional ofcourse if you want to increase your speeds.

✔️ Full Self Custody 
NO telegram bot, NO webapp, FULL control over your private keys, fully self custody.

LIFETIME PRICE: 7 SOL

(https://t.me/m00nb0t)










----------------------------------------- 1: Buy Modes -------------------------------------------
1: Bundle Buy (JITO): Enter token address (CA) this mode will bundle buy with your 20 wallets.

2: Auto Volume (JITO):  This mode is unique, it will monitor the dev address from the config, and once it detects a new pump.fun launch it will automatically run the new human mode for generating volume. Human mode works like so:  Buy Buy Sell| Buy Buy Sell| Buy Buy Sell| Buy Buy Sell 
until every wallet has bought & sold, then it will restart until you either close the application or crtl + c quit the application.

3: Human Mode (JITO): Enter token address (CA) and delay when prompted. Human mode works like so:  
Buy Buy Sell| Buy Buy Sell| Buy Buy Sell| Buy Buy Sell until every wallet has bought & sold, then it will restart until you either close the application or crtl + c quit the application.

4: MicroBuy (SPAM):  Enter token address (CA) and delay when prompted. This mode will spam buy TX's with a little amount of SOL based on the config value, without JITO indefinitly until u close the application or ctrl + c to quit. 

5: BumpBot: Enter token address (CA), buy amount & delay when prompted. This mode will use THE FIRST WALLET inside wallet.txt and spam (non JITO) TX's buying & selling your token in the same TX, hit "x" and enter key to kill the infinite loop and return to main menu at any time

6: Warmup Mode: This mode will buy & sell recently traded tokens with a random sol amount between your MIN/MAX config values to generate human like activity so scanners or on chain bozos think they're not fresh wallets. 

----------------------------------------- 2: Sell Modes -------------------------------------------
1: Sell All (JITO): This mode will bundle sell all wallets to your desired percentage in one atomic bundle.

2: Single Sell: This mode will prompt you to enter the token address (CA) and to enter the (index) of the wallet you want to sell. It will then sell 100% of tokens in that wallet

3: Delay Sell: 

4: Cleanup Mode: This mode will bundle all the SUB wallets & sell ALL Pump.Fun tokens, essentially cleaning up ur wallets. 

5: Back to Main Menu: Enter X to return to main menu

----------------------------------------- 3: Wallet Modes -------------------------------------------

1: Gen Wallets: Generates wallets based on the amount entered when prompted, stores them in /keypairs folder along with wallets.txt

2: Check Balances: Checks the SOL & SPL Token balance of every wallet

3: Close Token Accounts: Closes SPL Token Accounts of each wallet reclaiming the rent fees

4: Create Profiles: Creates profiles on Pump.Fun (Username + Bio)

5: Unwrap Wsol: This will swap your wsol for Sol, after trading on pumpswap.

----------------------------------------- 4: Transfer Modes -------------------------------------------

1: This mode will transfer SOL from ur main wallet (Sender from config file) to EVERY sub wallet you have in wallets.txt/keyapirs directory

2: This mode will send SOL from every VOLUME/SUB wallet back to the desired MAIN wallet address (NOTE 0.0009 SOL)  will remain in every wallet you will need to manually send this back if u want it

3: This mode will send 100% of the token balance in the VOLUME/SUB wallets to the wallet address you provided when running!

4: Quit:  Quits the application

----------------------------------------- 5: Launch Token -------------------------------------------

1. Bundled Launch: Launch your token and buy with 20 sidewallets in the same first block. No snipers guaranteed. Choose either randomized min max, from the Config, or amount per wallet.

2. Normal Launch: This will launch your token normally, allowing you to dump on snipers, and you can buy up supply after.

----------------------------------------- 6: Airdrop Monitor -------------------------------------------

This mode will monitor your launch wallet for the launch, move your dev holdings to a proxy wallet, and airdrop to your side wallets from there, creating a distribution. It will keep 5% in the launch wallet.

----------------------------------------- 7: Comment Bot -------------------------------------------

Configure your comments in the commentsconfig file, and this mode will use your sidewallets to comment on your desired token with configurable delay.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------



Seperate Scripts:

----------------------------------------- Vanity.js -------------------------------------------

This script will grind vanity contract adresses for your launches, and save them to a json file. They will be automatically loaded as options when launching. To use it, in terminal type:

-node vanity.js suffix pump         ---> h9813h9ueh9h2"pump"

or

-node vanity.js prefix ass          ---> "ass"ahfiauwhfsisfs


----------------------------------------- recoverluts.js -------------------------------------------

This script will recover rent funds from the lookuptables you need to generate to perform a bundled launch, and bundled sells. To recover your funds you need to run this TWICE with about an hour in between. To use it, in terminal type:

-node recoverLUTs.js
