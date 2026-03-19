# Trading Matrix for EVE Online
Trading Matrix for EVE Online – The Comprehensive User Manual
Welcome to Trading Matrix, your ultimate tool for trading and industry in EVE Online. This guide will walk you step by step through every function, tab, and button in the software, as if you were opening it for the very first time. No shortcuts, no skipped details – here you’ll find everything you need to know to hit the ground running.

1. Basic vs. Premium: Which Version Suits You?
Before we dive into the individual windows and tabs, it’s important to understand that Trading Matrix offers two usage models:

The Basic Version (Free)
The Basic version gives you access to the core functions of the software. It’s perfect for beginners, casual traders, or pilots who only want to scan the market occasionally. However, the Basic version comes with certain limitations: For instance, you may have a limit on the number of items you can save in your Favorites, you might only be able to link a limited number of accounts (via ESI), or you’ll have access to a reduced search limit in the Analyzer.

The Premium Version
The Premium version unlocks the full, unlimited potential of Trading Matrix. This version is aimed at power traders, industrial tycoons, and multi-boxers. Here, you enjoy an unlimited number of linkable accounts (crucial for players with multiple trading or production characters), can create endless Favorites lists, and always have access to instant, unlimited live market scans, as well as the most advanced industry calculation tools.

2. The Global Dashboard (Sidebar and Settings)
Once you open the software, you’ll find the main menu (Dashboard/Sidebar) on the left side or at the top. Before you start calculating, you must define the essential “rules of the game” here that the program will use for its calculations.

HUBS (Trade Hubs)
A Hub is a central trading system in EVE Online (the major supermarkets of the universe).

How it works: In this dropdown menu, you select your primary marketplace – in 90% of cases, this is Jita 4-4, but it could also be Amarr, Dodixie, or Rens.

What it’s for: The selected Hub tells the entire tool where to pull price data (buy/sell) from. When you calculate within the Matrix, the purchase prices for materials are always based on the data from the Hub selected here.

ADD ACC (Link Accounts)
This is one of the most important buttons in the tool. It connects Trading Matrix directly and securely to the game via the official CCP API (ESI).

How it works: When you click “Add ACC” (Add Account), your browser opens the official EVE Online login page. You log in with your account and select the character that will be trading or producing. You then grant the app permission to read your wallet data, market orders, and industry jobs (it is completely safe; the app cannot trade for you).

What it’s for: This allows your in-game orders (buys/sells), your live balance, and your ongoing production jobs to be loaded fully automatically into the tool. Manual typing is a thing of the past.

Target Station (Your Operating Base)

How it works: A “Target Station” is distinct from the Hub. It’s the specific station or citadel (Upwell structure like an Azbel or Keepstar) where you actually trade or produce.

What it’s for: Upwell structures have their own tax rates set by the structure owners and offer industry bonuses. By entering your actual operating base here, the tool can calculate, for example, that you build your items in the Sotiyo in Perimeter, but buy your materials in the Jita Hub.

3. Taxes (Tax Settings)
In EVE Online, taxes eat up a significant portion of your profits. The Taxes tab (often found within Settings) must be configured correctly before you trade anything!

Broker Fee: This is the percentage of tax you pay when you create an order. Set this slider/text field exactly to the value you see in the in-game market window. It depends on your skills and standings.

Sales Tax (Transaction Tax): The tax incurred on every successful sale. It depends on the Accounting skill.

SCC Surcharge: Usually calculated automatically or can be set (relevant in citadels).

Industry Facility Tax: Taxes for production (blueprint installation costs).

Function: The Matrix takes these numbers and will automatically deduct them from every calculated profit result from now on. So, if the “Analyzer” shows a profit of “1 Million ISK,” that’s the amount you’re guaranteed to have after all the taxes entered in the Taxes tab have been deducted!

4. Analyzer (The Market Scanner / Jita Analyzer)
The Analyzer tab is the command center for the station trader. Here, you can automatically search for items worth flipping (buying low, selling high).

Filter Options (Header Row)

Search Bar: You can search for specific items or entire groups (e.g., “Drones” or “Missiles”).

Daily Volume (Trading Volume): A slider or input field. Here you specify: Show me only items that are traded at least 100 times per day. An item that makes 100 million profit but is only bought twice a year is useless to you as a trader.

Margin Filter (%): Show me only items with a profit margin above 10%.

Min/Max Price: Filters out ships or modules that simply exceed your budget.

The Results View
After clicking the Scan button (or automatically generated), you’ll see a list:

Buy Price: At what price can you currently acquire the item cheaply (Top Buy Order in the Hub)?

Sell Price: At what price could you immediately list it for sale?

Net Profit: Your real profit margin in hard ISK (after all taxes!).

Margin & ROI: How profitable is the item compared to the ISK capital you invested, shown as a percentage.

The Favorites Button (Star / Heart)
Next to every item displayed in the list, you’ll find this button. If you find a lucrative item in the Analyzer, click this button. The item will then be permanently saved for the future in the Favorites tab.

5. Favorites (Your Daily Working Portfolio)
Instead of running the massive Analyzer search every single day, you build your own portfolio in the Favorites tab.

How it works: When you click this tab, Trading Matrix immediately queries the EVE server data live for precisely these selected items.

What it’s for: It’s your daily workspace. In 5 seconds, you can see if the items you saved yesterday are still profitable today. If margins have crashed, you remove the items from the list again via the star button and switch to others.

6. Order Tab (The Live Order Tracker)
The Order tab is your in-game market window – on steroids. Once you’ve added an account via “Add Acc,” this window will populate.

Functions and Subtabs:

Active Orders: A tabular list of all your current buy and sell orders in the game.

Outbid Indicator (The 0.01 ISK War): The tracker’s coolest feature. The tool compares your in-game orders live with the market. The Matrix highlights items (e.g., yellow/red) if someone in the game has outbid your buy order or undercut your sell order. You immediately know: I need to adjust my order in-game (Update) to stay at the top.

Profit History / FIFO Batches: If you buy 10,000 units of ore in multiple batches and sell them in multiple parts, Trading Matrix handles this using the “First-In, First-Out” principle. This tab calculates exactly which batch generated which real profit for you (often in a “History” or “Completed” section).

Totals / Escrow: A display showing how much ISK you currently have tied up in orders (escrow) and the total value of goods you have listed on the market.

7. Industry Tab (Production Matrix)
This tab is for pilots who want to craft items themselves. Here you can find out, down to the last ISK, whether it’s worth starting production on a Blueprint.

Blueprint Configuration:

Item Selection: You choose what you want to build (e.g., a “Dominix” Battleship).

ME (Material Efficiency) / TE (Time Efficiency): Here you enter (via dropdown or buttons) how researched your in-game Blueprint is (e.g., 10% ME).

Facility & Rig Setup: If your facility has a bonus (e.g., T2 Standup Rigs in a station), you select that here.

The Results Analysis:
The tool calculates everything and provides you with:

Material List: All base materials (Tritanium, Nocxium, etc.) required, with exact reduced quantities (thanks to your ME/Facility settings).

Material Cost: Fetches the price of ALL these materials live from the configured Hub.

Build Cost: The sum of all material costs PLUS the job installation taxes.

Market Price: The expected selling price of the Dominix in the Hub.

Production Profit: The final comparison. If this number is red, it means you’ll lose a lot of money building it – you’re better off buying the ship directly from the market. If the number is a healthy green, start production!

Conclusion: Trading Matrix completely eliminates the guesswork, the endless checking of third-party sites, and the hours of Excel calculations from EVE Online. Take the first 5 minutes to correctly set up “Taxes,” “Hubs,” and your “Account (Add Acc),” scan a few items into your Favorites, and then rely on the “Order Tracker.” Fly safe, and happy investing!

:globe_with_meridians: Try it NOW — for FREE

:link: https://trading-matrix.com
