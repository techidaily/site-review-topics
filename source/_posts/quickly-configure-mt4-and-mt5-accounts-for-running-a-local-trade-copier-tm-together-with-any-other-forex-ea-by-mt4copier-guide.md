---
title: Quickly Configure MT4 and MT5 Accounts for Running a Local Trade Copier™ Together With Any Other Forex EA
date: 2024-02-26 13:59:31
tags: 
  - mt5
  - mt4
categories: 
  - apps
description: Quickly configure MT4 and MT5 accounts for running a Local Trade Copier™ together with any other Forex EA. In this video, Rimantas explains how to do it. - Quickly Configure MT4 and MT5 Accounts for Running a Local Trade Copier™ Together With Any Other Forex EA
keywords: mt4 to mt5 trade copier,mt4 to mt5,mt4 to mt5 trade,meta trader
---

The [Local Trade Copier](https://tools.techidaily.com/mt4copier/) software is a powerful tool that allows you to copy trades between multiple MetaTrader 4 and MetaTrader 5 accounts. It is a perfect solution for money managers and signal providers who need to manage multiple accounts at the same time. The LTC software is also a great tool for traders who want to copy trades between their own trading accounts.

In this guide, we will show you how to configure your MetaTrader 4 and MetaTrader 5 accounts to run the [Local Trade Copier](https://tools.techidaily.com/mt4copier/) together with any other Forex EA.

<iframe width="898" height="503" src="https://www.youtube.com/embed/TiaPtSBhguQ" title="Set up MT4 &amp; MT5 Accounts to Copy and Paste Trades From One Forex EA Across Many Metatrader Accounts" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Pricing

- **Local Trade Copier™ for MT4 & MT5 (Personal Monthly Plan)** : [$31.47/month](https://secure.2checkout.com/order/cart.php?PRODS=4722887&QTY=1&AFFILIATE=108875)
- **Local Trade Copier™ for MT4 & MT5 (Manager Monthly Plan)** : [$96.58/month](https://secure.2checkout.com/order/cart.php?PRODS=4723269&QTY=1&AFFILIATE=108875)
- **Local Trade Copier™ for MT4 & MT5 (VIP Monthly Plan)** : [$215.95/month](https://secure.2checkout.com/order/checkout.php?PRODS=4723270&QTY=1&AFFILIATE=108875)
- **Local Trade Copier™ for MT4 & MT5 (Personal Annual Plan)** : [$314.71/year](https://secure.2checkout.com/order/cart.php?PRODS=4723646&QTY=1&AFFILIATE=108875)
- **Local Trade Copier™ for MT4 & MT5 (Manager Annual Plan)** : [$965.83/year](https://secure.2checkout.com/order/cart.php?PRODS=4723648&QTY=1&AFFILIATE=108875)
- **Local Trade Copier™ for MT4 & MT5 (VIP Annual Plan)** : [$2159.55/year](https://secure.2checkout.com/order/cart.php?PRODS=4723650&QTY=1&AFFILIATE=108875)




## MAAB Trade Filter: Copy Master Account Only When It Is Making Profits

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/1.png)

All strategies have drawdowns or periods when they face unfavorable market conditions. MAAB Trade Filter is specifically made to reduce negative effects on your account when combined with the [Local Trade Copier](https://tools.techidaily.com/mt4copier/). It is an easy solution to minimize drawdown and copy Master Account only when it is making profits. This tool also has the power to turn bad EAs and strategies into winners. Find out how MAAB Trade Filter makes it happen in this guide.

### MAAB Trade Filter – How it Works

MAAB stands for Moving Average on Account Balance. As traders, we open and close trades, and the account balance moves up and down, creating a histogram. Now, plotting a Moving Average on top of the balance histogram we instruct MAAB Trade Filter not to allow losing trades to take effect. Losing trades that make the balance or equity below this Moving Average are simply filtered out. They are not copied from the Master account to the Client account. Once winning trades makes the account balance histogram go above the Moving Average, MAAB Trade Filter will allow them to grow the Client account. A simple, yet unique solution to effectively protect Client accounts.

In the picture below you can see the Master account where the purple background is. MAAB Trade Filter indicator is also visible here. The Client account is just below. This example shows two MAAB Trade Filters applied from two Master accounts.  It is just a demonstration that you can merge multiple MAAB Trade Filters into one Client account.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/2.png)

MAAB Trade Filter tracks one Master account. However, you can stack up multiple MAAB Trade Filters to track multiple Master Accounts. Very useful if you have different strategies from multiple Master accounts and want to filter those who are not currently making profits. This way, the Client EA only receives trades from winning Master accounts. MAAB Trade Filter can also work in reverse mode if you need it.

Note that the red Moving Average you see on the Master account histogram is just for your reference. The Moving Average on the Client-side is the one that will be used by Client EA for filtering. Just to avoid confusion if you use different Moving Average settings on those accounts.

### Setting up your MAAB Trade Filter

1. First things first, set your MAAB Trade Filter indicator on the server-side, on your Master account. The MAAB Trade Filter will scan every closed trade on the Master account and then send the signal to Client accounts, if applicable.
2. Secondly, plug-in MAAB Trade Filter to your Client account too. MAAB Trade Filter histogram you see on the Client account shows the account balance from the Master account, not the Client account balance. The reason behind this is to show you what trades are filtered out from the Master account.
3. After you plug in MAAB Trade Filter on the Client-side you need to type in the account number you want it to track. In the top right part of the picture below, we use account number 60055865 as an example:
   ![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/3.png)
4. Now, we need to enable MAAB Trade Filter on the Client EA. It may look like it is automatically enabled once you see the visuals, but we need to turn it on from the Client EA settings window. Scroll to the Trade Filter section and set it to True.
   
We are ready now to put MAAB Trade Filter into action! But make sure you understand all of MAAB Trade Filter powers and how to adjust it to your preference. In the next section, we will demonstrate exactly that.


### MAAB Trade Filter Features Demonstration

So, I have my VPS up and four MetaTrader accounts running on it. MetaTrader 4 will be my Master account #1, and MetaTrader 5 will be my Master account #2. On the right side, I have two Client accounts, running on MetaTrader 4 and MetaTrader 5.  Now, both Client accounts will copy trades from both Master accounts, however, MAAB Trade Filter will be engaged so we can see how it filters undesirable trades.

First, I will set up my server-side Master accounts. Open MetaTrader 4 and apply Server EA to the chart (drag n drop) from the Experts list. You will need to have at least version 2.9.9 of the EA to make it work with the MAAB Trade Filter. Click OK and do not worry about settings now.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/4.png)


Now go to the MT4 Indicator list and apply the “MA on Account Balance (server)” indicator to the chart too. No need to change the settings, however, if you need it to track an EA with a specific Magic Number you have that option available. Otherwise, a setting of 0 means it tracks manual trading. If you set the Magic Number input to -1 it will track all the trades on this account.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/5.png)

If you zoom into the histogram, you will notice each histogram bar represents how closed trade affected the balance. A mouse-over tooltip above the indicator will display balance information on each bar. Notice that the histogram went down as losing trades closed and it went just below the Moving Average. At that point, MAAB Trade Filter would stop accepting trade signals from this Master account.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/6.png)

Now I will set up a Metatrader 5 account, my second Master account. I can repeat the same procedure as for the first Master account. I apply the Server EA for the MT5 (at least version 1.1.6), then attach the MAAB Trade Filter indicator dedicated for the MT5 server-side. Notice this second Master account has a balance histogram below the filtering Moving Average, meaning it has a series of losing trades. We do not want these losing trades on the Client account, don’t we? That is why we filter them out using the MAAB Trade Filter.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/7.png)

Moving on to the Client account on MT5. Here I will first insert the MAAB Trade Filter indicator for the client-side onto the MT5 chart window. A settings window will pop up and it will show a few options. You can change the Moving Average periods (default 13), MA types like Simple, Exponential, Smoothed, etc. For the MAAB Trade Filter to work, we must input the Master account number in the ServerAccountNumber field. No worries, in case you forget to type in the number the indicator window will display a warning.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/8.png)

In my example, the Master account number is 60055865. Again, the indicator will now show the Master account balance, not the Client account balance.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/9.png)

Finally, I can attach the Client EA now onto the chart. In the EA settings, scroll down and find the MA Trade Filter line and set it to True. Right below you will also see the option to apply the Moving Average to the Master account balance histogram or account’s equity.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/10.png)

Regardless of your preference, The MAAB Trade Filter indicator will show an orange horizontal line that represents the current equity of the Master account. It will refresh every 15 seconds or so. As we see, the balance of this Master account is above the Moving Average so the Client EA will copy the trades to the client side.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/11.png)

If you want to set the Moving Average to 50 periods, of course, this will also affect how the MAAB Trade Filter indicator behaves. With a 50-period Moving Average, the histogram balance is now below the MA, meaning the MAAB Trade Filter will cease copying trades from this Master account. Since the 50 period MA reacts slower to the histogram changes, it will need more winning trades before the histogram is above the MA(50). Only then the Master account trades will be allowed again to the Client account.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/12.png)

For now, let’s change back the MA period settings to 13.

While I am still on this client-side platform, I will add the MAAB Trade Filter for the second Master account (the MT5). I will insert the MAAB indicator (client-side) into the chart and input the Master account number in the settings.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/13.png)

Now we can see two indicator windows showing the balance histogram from each Master account.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/14.png)

When we have a Client account setup like this, the MAAB Trade Filters will cease copying trades for any Master account that does not qualify. To qualify they need to have a histogram above the Moving Average you set.

Finally, we have a second Client account that we want to improve with MAAB Trading Filter. I will attach the MAAB Trade Filter (client-side) indicator first and then set it to connect with the first #60055865 Master account in the ServerAccountNumber field.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/15.png)

Now we add the Client EA v2.9.9f from the Experts list and enable it from the settings window. This time I will also set the EA to compare the Moving Average to equity instead of the account balance.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/16.png)

Check out the orange Equity line. It is below the Moving Average right?

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/17.png)

Because of this, all trades from this Master account will be suspended until the equity goes above the Moving Average.

### MAAB Trade Filter in Action Examples

Let’s go ahead and make some trades to see how MAAB Trade Filter manages trading from winning Master accounts and from those that currently do not show good performance. I already have a lot of trades open so I will pick one currency pair that does not have any. It is the USDJPY.

Let’s buy half a lot on the first Master account (#60055865) and see what happens on the Client-side platforms.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/18.png)

As expected, the first Client account immediately copied the trade. The account balance from the Master account was above the Moving Average.

However, the second Client account denied that trade. This is because we set the rule to compare the MA to Master’s equity – which was below the MA. We can confirm this by looking at the Experts tab and the line that says “Ignored trade BUY USDJPY because of the MAAB Trade Filter. Master account equity below MA13”. Clearly said, it is doing what we set it to do.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/19.png)

Even though the balance histogram was above the MA for this Master account, the equity was not. Once the equity goes above MA(13) the MAAB Trade Filter will allow it to pass to the Client account.

Trades that are ignored by the system will also trigger the question mark on the main chart screen to turn red.  A counter for all ignored trades is available too.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/20.png)

Let’s do some more trading from the other Master account. EURUSD looks like a good example, buying 1 lot. This trade is sent to two Client accounts we have linked, but let’s see if it is filtered on any.

The first Client account ignored this EURUSD trade, but the second Client account accepted it. Simply because we did not set up the second MAAB Trade Filter for this Master MT5 account on the second Client account. All trades that come from the Admiral Markets Master account to the IC Markets Client account are copied without any filtering.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/21.png)

If we go to fullscreen we can see the message in the Experts tab that trades from one of the Master accounts are ignored. The reason is “Master account balance is below MA13”. Perfect! That is what we want.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/22.png)

Now let’s see what happens when we close this EURUSD trade. It is in a small profit. Alright, the histogram went up a bit as the balance increased by the profit amount. The equity was updated too. On the Client side, the same balance and equity changes are also visible.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/23.png)

I will find and close some trades in a loss so I can show you what happens in this case. In the screenshot below, you can see that the loss caused the balance to go down which can be seen on the balance histogram going below the Moving Average.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/24.png)

This means MAAB Trade Filter will no longer allow trades to this Client from either Master account. They both do not pass the filter rules we have set in the MAAB Trade Filter. To test this I will open a new USDJPY trade. As expected I see a “sell USDJPY ignored” message on the Client (see screenshot below), good job!

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/25.png)

Since I have some trades in profit too I will close them to see what happens.

After I close a profitable trade, the balance goes up and its histogram goes above Moving Average again!

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/26.png)

Does it mean the MAAB Trade Filter will now allow this Master account trades to the Client-side? Let’s test it out, I will make another USDJPY trade.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/27.png)

Alright, the first client copied this trade, however, the second Client account did not. If you remember, there is a rule for MAAB Trade Filter we set – If equity is below the MA, ignore trades from this Master account. It just does what is supposed to do.

### MAAB Trade Filter Reverse Logic

I open the Client EA settings on the first Client account (the one with two MAAB Trade Filters) and set the MAAB Reverse Logic parameter to True.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/28.png)

I will also set the Reverse Trades to True under the Trades Manipulation settings section in the Client EA.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/29.png)

Click OK and then open the Client EA settings on the second Client account (the one with just one MAAB Trade Filter set to compare equity). Now, let’s keep the equity rule and change MAAB Reverse Logic to True.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/30.png)

Ok, now the first Client account has the EA instructed to use MAAB Reverse Logic and also reverse trades, meaning “buy” trades become “sell” trades and “sell” trades become “buy” trades.

The second Client account has MAAB Trade Filter set to compare MA to Master account equity but with Reverse Logic – meaning if equity is below the MA trades are copied to the Client account and if above they are filtered. Let’s test this setup with a trade now.

Opening USDJPY “buy” trade…

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/31.png)

The second Client account with the reversed equity rule was allowed to copy trades. Makes sense since the equity is below the MA. Before the Reverse Logic change, all trades were filtered.

Meanwhile, the first Client account ignored this USDJPY trade. The Reverse Logic denied it now since the balance is above the MA. Normally, the MAAB Trade Filter would allow it, however, we have reversed its logic.

But what will happen if I open a EURUSD “buy” trade on the second Master account, the one with reversed trade logic? My “buy” EURUSD trade gets copied as “sell” EURUSD.

![](https://tools.techidaily.com/images/apps/mt4copier/maab-trade-filter/32.png)

The second Client account copied the trade normally since we do not have any MAAB Trade Filter enabled for this Master account.

The first Client account is a different story though. The Master account has a balance histogram below the MA. Normally, it would not be allowed to the Client-side, yet we have inversed its logic. With the Reversed Trade enabled too, the “buy” EURUSD becomes “sell” EURUSD.

After all this, you might be wondering why would we need all this inversion? Well, this is a perfect solution for all Reversal trading strategies! It makes sense to reverse trades from a losing account, right? Why not make bad, losing strategies profitable? And with the MAAB Filter reverse logic, we are going one step further – we copy bad losing strategies (and reverse their trades) only when the Master account is losing. It is funny but true, now you can start composing bad strategies as well, and make use of all those EAs or strategies you have thrown into the trash bin.



## How To Copy Your Forex and Gold Trades From MT4 to MT5 in One Click

If you are a Forex trader who uses MetaTrader 4 and MetaTrader 5, you may want to copy your trades from one platform to another. This can be a great way to diversify your trading and take advantage of the unique features of each platform. In this guide, we will show you how to copy your Forex and Gold trades from MT4 to MT5 in one click.

<iframe width="898" height="503" src="https://www.youtube.com/embed/Xgj2mFUI5qE" title="How To Copy Your Forex and Gold Trades From MT4 to MT5 in One Click" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

In this video, Rimantas shows how to copy your Forex and Gold trades from MT4 to MT5 in one click using the [Local Trade Copier](https://tools.techidaily.com/mt4copier/) software, even if you’ve never linked accounts before.

Have you ever played with walkie-talkies? You press a button, say something, and your friend hears it on their walkie-talkie, even if they’re far away. It’s like magic, right? Well, Rimantas has a similar kind of magic trick to show you in this video, but it’s for your Forex and Gold trades.


Imagine MT4 is your walkie-talkie, and MT5 is your friend’s walkie-talkie. Normally, if you wanted to tell your friend something, you’d have to walk over to them and say it. But with walkie-talkies, you can just press a button, and they hear you! Rimantas is going to teach you how to press that magical button for your trades. With just one click, you can send your Forex and Gold trades from your MT4 walkie-talkie to your friend’s MT5 walkie-talkie. It’s that simple!

Now, let’s think of another fun analogy. Have you ever listened to the radio? Radios are amazing. You turn them on, and you can hear music or people talking from far away places. It’s like they’re broadcasting their voice all over the city, or even multiple cities. That’s what you can do with your trades. You can broadcast them from MT4, just like a radio station sends out songs to many places. And the best part? You can do it in just a few seconds!

You might be thinking, “But I’m not a DJ at a radio station. How can I do this?” Don’t worry! Rimantas is here to help. He’s like the best radio DJ teacher you could ever have. He’ll guide you step by step, showing you how to turn your MT4 into a powerful radio station that can send your trades to MT5. And you don’t need to be a trading expert or a radio DJ to do it. It’s as easy as turning on your favorite song on the radio.

And guess what? You won’t need a bunch of gadgets or devices. It’s not like trying to juggle three balls at once. No, it’s much simpler. Just one click, and your trades fly from MT4 to MT5, just like a song travels through the airwaves to reach radios in many homes.

Maybe you’re a little nervous. Maybe you’re thinking, “What if I make a mistake? What if I’ve never done this before?” It’s okay to feel that way. Remember the first time you tried to ride a bike? It was a bit scary, right? But with someone guiding you, holding the bike steady, you learned. And soon, you were riding all by yourself, feeling the wind in your hair. That’s what Rimantas is here for. He’s like that person holding the bike for you, making sure you don’t fall. He’ll show you everything, even if you’ve never linked accounts before.

So, get ready for an exciting journey. By the end of this video, you’ll be broadcasting your trades like a pro radio DJ, reaching MT5 with ease. You’ll achieve more, with less effort, and have a lot of fun along the way. Tune in, and let Rimantas show you the magic of trading!

## How To Share Your Winning Forex Trades With Friends and Family

If you are a successful forex trader, you may want to share your winning trades with friends and family. This can be a great way to help them learn about forex trading and potentially make some money. There are a few different ways you can share your trades with others, so let’s take a look at some of the most popular options.

<iframe width="898" height="503" src="https://www.youtube.com/embed/g6GCO8K7R2k" title="How To Share Forex Trades With Friends and Family" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

In this video, Rimantas explains how to share your winning Forex trades with friends and family’s accounts so everyone can enjoy success together.

The [trade copier](https://tools.techidaily.com/mt4copier/), a tool often used in Forex trading, can be advantageous for several reasons when it comes to sharing trades with friends and family. Here are five reasons why it helps people:

1. **Ease of Managing Multiple Accounts**: It allows a trader to manage several accounts simultaneously. This means if someone is proficient in trading, they can easily replicate their trades across friends and family’s accounts, ensuring everyone benefits from the successful strategies.
2. **Real-Time Sharing**: The trades are copied in real-time. This synchronization means that friends and family will enter the market at virtually the same time and price as the main account, maintaining the strategy’s integrity and performance.
3. **Educational Opportunity**: For friends and family who are new to Forex trading, observing and engaging in trades through the copier can serve as a valuable learning experience. It allows them to see strategies in action and understand market movements without the need to make all the decisions themselves initially.
4. **Efficiency and Convenience**: Automating the trade copying process saves time and reduces the chance of error in trying to manually replicate trades across multiple accounts. This efficiency means more time can be spent analyzing the markets and refining strategies.

Overall, the [Local Trade Copier](https://tools.techidaily.com/mt4copier/) can democratize access to trading strategies, allow for shared learning experiences, and potentially increase the profitability for all involved parties through shared knowledge and resources.


## How to set different lot sizes for each copier account

<iframe width="898" height="503" src="https://www.youtube.com/embed/K6JwObVWivU" title="How to set different lot sizes for each copier account" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

In this video, Rimantas explains how you can easily set different lot sizes for each copier account with the [Local Trade Copier](https://tools.techidaily.com/mt4copier/)™ for MT4 & MT5.

## How To Configure MT4 and MT5 Accounts for Running a Local Trade Copier™ Together With Any Other Forex EA

The [Local Trade Copier](https://tools.techidaily.com/mt4copier/) software is a powerful tool that allows you to copy trades between multiple MetaTrader 4 and MetaTrader 5 accounts. It is a perfect solution for money managers and signal providers who need to manage multiple accounts at the same time. The LTC software is also a great tool for traders who want to copy trades between their own trading accounts.

In this guide, we will show you how to configure your MetaTrader 4 and MetaTrader 5 accounts to run the [Local Trade Copier](https://tools.techidaily.com/mt4copier/) together with any other Forex EA.

<iframe width="898" height="503" src="https://www.youtube.com/embed/TiaPtSBhguQ" title="Set up MT4 &amp; MT5 Accounts to Copy and Paste Trades From One Forex EA Across Many Metatrader Accounts" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


Today, I’m diving into a game-changing tool that’s going to make your trading life a whole lot easier and way more profitable. In this video, I talk about the [Local Trade Copier](https://tools.techidaily.com/mt4copier/)™ and how it’s going to save you from buying a Forex EA license for every single one of your MT4/MT5 accounts. Yes, you read that right!


Imagine this: You’ve got a Forex bot that’s making some really smart trades in Forex, Gold, Oil, and other markets. It’s working its magic on your MT4/MT5 account, and you’re seeing some sweet profits roll in. But what if you have multiple Metatrader accounts and want them all to get in on the action? 🤔

In the past, you’d have to buy a separate Forex EA license for each and every account. Not only does that get pricey, but it’s also a lot of extra work to manage all those licenses and accounts. But hold on to your trading hats because there’s a brilliant solution: [Local Trade Copier](https://tools.techidaily.com/mt4copier/)™ software!

If you are looking at how to configure MT4 and MT5 accounts to copy and paste trades from one EA to many other Metatrader accounts, then this is exactly what you need.

**🚀 One License, Unlimited Trading Power 🚀**

With the [Local Trade Copier](https://tools.techidaily.com/mt4copier/)™, you can copy and paste those successful trades from your Forex bot to as many Metatrader accounts as you want, all without buying extra licenses. It’s like having a superpower where one smart trade decision gets multiplied across all your accounts, maximizing your profits without maximizing your expenses!

**🛠️ Easy-Peasy Setup for MT4 and MT5 Accounts 🛠️**

Now, you might be thinking, “This sounds great, but is it complicated to set up?” Nope! In this video, I am going to walk you through the whole process, step by step. I’ll show you how to get your MT4 and MT5 accounts configured and running smoothly with the [Local Trade Copier](https://tools.techidaily.com/mt4copier/)™ and any Forex EA, without any tech headaches. Stop buying Forex EA license for every MT4/MT5 account and watch this video.

## Easy Way to Copy Trades of Equal Lot Size for All Accounts

<iframe width="898" height="503" src="https://www.youtube.com/embed/TwthTCQm74A" title="Easy Way to Copy Trades of Equal Lot Size for All MT4 &amp; MT5 Accounts" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

In this video, Rimantas explains how to make every MT4 & MT5 Client account use the same lot size as the Main account with the [Local Trade Copier](https://tools.techidaily.com/mt4copier/)™ for MT4 & MT5. It is an easy way to copy trades of equal lot size for all Metatrader accounts.
<ins class="adsbygoogle"
    style="display:block"
    data-ad-format="autorelaxed"
    data-ad-client="ca-pub-7571918770474297"
    data-ad-slot="1223367746"></ins>
