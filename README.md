# Trading-Options-with-CFDs-IG-Academy
IG Academy -- Trading Options with CFDs

## What are options?

* An option is a contract that lets you trade on the future value of a particular financial asset.
* When you buy an option, you are paying a premium for the right to buy or sell the asset at a set price, on or before a set date when the option expires.

### How options work

There are two types of options: Calls and Puts.

* A ***call*** gives you the right, but no obligation, to buy an asset at a set price on or before a set date.
* A ***put*** gives you the right, but no obligation, to sell an asset at a set price on or before a set date.

* Buy a call option, and you take a long position on its underlying asset. The more the price rises, the more profit you can make and vice versa.

* Calls and puts both have an ***expiry date***. You don't have to buy or sell if the market doesn't move the way you expected, but once either option expires, it will become worthless. You ***lose*** the premium you paid for it, but nothing more.
* You could sell your option itself without ever exercising it - known as closing out - profiting from the price movement without committing a great deal of capital.
* If the market doesn't move in the way you expected, you don't have to exercise your option, limiting your losses to what you paid for the option itself.

### How options can generate a profit

* When you buy an option contract, you aren't physically buying anything - no asset is actually transferred.
* When you decide to exercise an option, on the grounds that doing so will earn you a profit, it gives you the right to buy the underlying asset from the option seller.

### Understanding the terms

* ***Holders and writers***: the buyer of an option is the holder, while the seller is the writer. In a call, the holder has the right to buy the underlying asset from the writer. In a put, the holder has the right to sell the underlying asset to the writer.
* ***Premium***: the fee paid by the holder to the writer for the option.
* ***Strike price***: the price at which the holder can buy or sell the underlying asset.
* ***Expiry***: the date and time when the options contract terminates. After expiry, the option is owrthless. If the underlying market doesn't hit the strike price before expiry, the holder can't earn a profit.
* ***In the money***: when the underlying market's price is above the strike or below the strike, meaning the holder can exercise the option and trade at a better price than the current market price.
* ***Out of the money***: when the underlying market's price is below the strike or above the strike, meaning that exercising the option will result in a loss.
* ***At the money***: when the underlying market's price is equal or very close to the strike.

### What does options trading cost?

* The cost of opening a position with IG includes an option premium and the dealing spread - the difference between the bid and ask price. The more likely it is that an option will move above or below the strike price, the higher its premium will tend to be.
* There will be no commission for CFD options - IG's only charge is the spread.

### How do options prices work?

* Options pricing is complicated and doesn't always move one-for-one with the underlying asset.

At IG option prices are set by the dealing desk, based on three key factors:

* ***The time to expiry*** - the longer an option has before it expires, the more time the underlying asset has to hit the strike price, so the premium will be higher.
* ***The current level of the underlying market*** - the closer the underlying asset is to the stirke price, the more likely it is to hit and pass the strike price.
* ***The volatility of the market*** - the more volatile the asset, the more likely it is that the option will hit its strike price. So options in a volatile market will see higher premiums.

## What are the benefits of trading options?

* If the market is rising, you can make money by buying an asset below the market with a call option.
* Alternatively, if the market is falling, a put option lets you sell an asset at a set price above the market.
* If the markets go flat, with many forms of trading there's not a lot you can do except hold on and hope things improve.

### Harnessing leverage

* Options enable you to trade using ***leverage***, meaning that the amount you pay to open is only a fraction of your trade's potential full value. This enables you to command a large position in a market with comparatively small payment.

### How are options used?

* ***Speculating with options***
* ***Hedging***: You could buy an option to sell the stock at a price that's close to its current level. Then if the stock's price falls, you can exericse your option and limit your losses. If your stock's price increases, then you have only lost the cost of buying the option in the first place.
* ***Profiting from volatility***

## How are options priced?

Some options are more expensive than others. Why is this?

* ***Underlying price***: Remember calls are right to buy, so sometimes the right to buy at the lower price is more desirable than the right to buy at the higher price, and so the value is greater.
* ***Time left to expiry***: The extra premium on top of the intrinsic value is called the ***time value***. The longer the time remaining to expiry, the greater the chance of further movements in the underlying asset and therefore the greater probability that the option may acquire intrinsic value.
* ***Option premium = intrinsic value + time value***: Options which have intrinsic value are described as being ***in the money***; Options which have no intrinsic value, and therefore only have time value, are described as being ***out of the money***; ***At the money*** is simply the option which has the closet strike price to the price of the underlying asset.
* ***Time decay***: the more time left to expiry, the more an option will cost. In other words, 
the time value of an option decays as the expiry draws closer, while the rate of decay increases as an option approaches expiry.
* ***Strike price***: At-the-money options will always have the greatest time value.
* *** Volatility***: If the volatility of security is high, there is a greater risk for an option writer, and they will demand higher premiums. If the volatility is low, the premiums required will be reduced.


### Interest rates and dividends

* The effect of changes in interest rates tends to be insignificant. Dividends paid out to shareholders by a company will cause the share price to drop by the amount of the dividend.
* Consequently, this will affect the price of options on that share.
* However, as the drop in share price is predictable, the impact of the fall will be priced into the premium well in advance.

## Managing the risks of options trading

* Properly used, options can help cap your risks.

### Buying an option

* When buying an option - either call or put - your maximum risk is equal to the premium paid. This is simply calculated as trade size multiplied by price.
* Buying options is therefore limited-risk, with a potential profit that is in theory uncapped if you buy a call.

### Selling an option

 * When you sell options, you receive the premium rather than pay it.
 * When you sell a put, the worst-case scenario is that the price of the asset falls to zero.

### Four other things to consider before trading options

* ***Complicated market***;
* ***Price volatility***: the more likely it is that an option will move above (calls) or below (puts) its strike price, the higher its premium will be.
* ***Time decay***: the value will diminish as it draws closer to expiring, making options extremely time sensitive.

## Buying options - some examples

### Buying a call

Imagine that an option on the FTSE 100 has a strike price of 6500. Let's say that the option has a preimum of 35. The expiry date is the third Friday in March.

There are several things that can happen by the point of expiry:

* On expiry, the price of the FTSE has risen from 6300 to 6453. The right to buy at 6500 is therefore worth nothing (it would cost more than buying the asset). You lose the premium paid.
* If the expiry price has risen to 6500, the index has reached the strike price of the option, but there is still no point in paying anything for the right to buy at the current level of the market. You still lose all of the premium paid.
* If the expiry has risen to 6530, say, the 6500 call would worth 30 points - the right to buy at 6500 has to be valued at 30 - the difference between the option and the actual price. However, this might not be enough of a difference to show a profit. You need to cover the cost of the premium.
* If the expiry is at 6535, the 6500 call would be worth 35 points. This is enough to cover your preimum - anything above it provides a real profit.

<img width = 75% height = 75% src = https://github.com/Louisli0515/Trading-Options-with-CFDs-IG-Academy/assets/128298224/d7f2cc6c-7632-4c6c-a321-4d4ef97406d2>

If you buy a call option, the risk is limited to the premium. 

The rewards are, in theory at least, unlimited when you buy a call option. The value of the call will increase with the value of the underlying asset, and the higher it goes, the greater the profits. Remember to deduct the premium of the call to calculate your profits.

### Buying a put

Imagine that the FTSE 100 is trading at 6500. Let's say that you buy a 6150 put option for a premium of 50 points. This means you have the right to sell at 6150 on the expiry date.


There are again several things that can happen by the point of expiry:

* Let's say that the expiry price is 6030. The right to sell at 6150 is worth 120 points. The option cost 50 points of premium, so that overall, the profit is 120 - 50 = 70 points.
* The breakeven point is 6100. Between 6100 and 6150 the option still has some value, which will be just enough to help recoup the premium paid. Above this, the option would be worthless. The loss would be the premium: 50 points.

<img width = 75% height = 75% src = https://github.com/Louisli0515/Trading-Options-with-CFDs-IG-Academy/assets/128298224/12cef199-25c7-4401-8ec8-8a8c9307343a>

You may not want to wait until expiry. The risk is limited to the premium when buying a put, the same as when buying a call.

The value of the right to sell increases as the underlying price drops. You would make the maximum profit if the underlying asset price fell to 0.

## Selling options

Selling a call, also known as making a short call or written call, can generate a profit when a long call (buying an option) would result in making a making a loss and vice versa.

The reason is that options are a decaying asset. Their value decays with the passage of time and they expire. This time decay works in your favour if you are an option seller. That's because the less time until expiry, the less chance the option has to go in the money. The option price becomes less valuable to the holder each day - befefiting the option seller.

A short call option can therefore create a limiteed profit in a short time.

The option seller makes a profit as long as the underlying price is below the strike price + the premium collected. The option buyer can profit only if the underly price goes above the strike price + the premium paid.

### Selling a call

This is a strategy that you might use if you were bearish about the prospects of the underlying market or if you thought the price was likely to stay the same.

The profit/loss profile of a sold call is the mirror image of the profile of a long call.

Let's take another example using the FTSE 100, with a strike price of 6500 and a 35-point premium, and look at the value of the sold call for different levels at expiry:

<img width = 75% height = 75% src = https://github.com/Louisli0515/Trading-Options-with-CFDs-IG-Academy/assets/128298224/9f8a32bc-eb29-4c1d-98bd-5c0dc26c113e>

If the underlying market is above the breakeven point of 6535 at expiry, you'll lose overall on the trade. If it expires at 6500 or below, you'll make a profit equal to the premium.

* Selling, or writing, a call option is a risky strategy. Your potential risk is unlimited, as the underlying price could theoretically increase to infinitey. If the market rises rapidly, you could suddenly find yourself with a runaway, uncapped loss.
* The maximum possible profit for writing an option is the premium.

### Selling a put

You would use this strategy if you had a neutral-to-bullish outlook for a particular market - so you thought the price was likely to stay the same or to rise.

The profit/loss profile for selling a put is exactly the opposite of the profile for buying a put. 

<img width = 75% height = 75% src = https://github.com/Louisli0515/Trading-Options-with-CFDs-IG-Academy/assets/128298224/ab5d9a46-b91b-4fbc-b08e-69e7e45eae81>

Let's consider the FTSE option with a strike price at 6150 and a 50-point premium.

If the FTSE is at or above 6100 on expiry, you'll make a profit. If not, you'll make a loss. Your maximum profit will be achieved if the FTSE is at or above 6150 on expiry.

* Selling a put option involves substantial risk, although your potential loss isn't completely unlimited, as it is when you sell a call option. The worst-case scenario occurs if the underlying asset drops to 0. This would give you a loss equal to the strick price - the premium.
* The maximum reward is the premium. 

## An introduction to the Greeks

* The Greeks are the measures of individual risks associated with trading options, so called because each one is identified by a Greek letter.

The main Greeks we will be using are:

* ***Delta***: the ratio that compares the change in the price of an asset to the corresponding change in the price of its option; It shows how much an option's price moves for every point of movement in the underlying asset. So delta is a measure of how movement in the underlying market will impact the price of your option, otherwise known as directional risk.
* Delta is often used in hedging strategies and is also referred to as the hedge ratio.
* Delta values can be positive or negative. The delta for a call option always ranges from 0 to 1. because as the underlying asset increases in price, call options increase in price.
* Put option deltas always range from -1 to 0, because as the underlying security increases, the value of put options decreases.
* ***In-the-money*** call options get closer to 1 as their expiry approaches.
* ***At-the-money*** options typically have a delta of 0.5, and the delta of ***out-of-the-money*** call options approaches 0 as expiry nears. The ***deeper*** in the money the call option, the ***closer*** the delta will be to 1, and the more the option will behave like the underlying asset.
* ***Vega***: how much an option's price moves when the volatility of the underlying asset changes. Vega represents the amount that an option contract's price changes in reaction to a 1% change in the implied volatility of the underlying asset. Vega changes when there are large price movements (increased volatility) in the underlying asset, and falls as the option approaches expiry.
* When you own options, you have a positive vega, whereas writing options carries a negative vega.
* ***Theta***: How much an option's price declines over time. It can also be referred to as an option's time decay. An option generally loses value as time moves closer to the maturity of the option. Thata is a negative number and can be thought of as the amount by which an option's value will decline every day.
* An option with high delta (usually one with a short-term expiry) will rapidly depreciate in value as it nears expiry.

## Simple strategy 1: trading delta

* Delta is a measure of how movement in the underlying market will impact the price of your option.

### Delta spread

* With delta spread you establish a delta-neutral position by simultaneously buying and selling options in proportion to the neutral ratio.
* In other words, the positive and negative deltas offset each other, so that the overall delta of the assets in question totals zero.
* The most common delta spread is a ***calendar spread***. This invovles constructing a delta-neutral position using options with ***different expiry dates***.

### What is the risk?

* With a delta spread, the maximum loss is approximately limited to the premium paid, but can increase if the underlying has a large move and the delta of the optiosn changes.

## Simple strategy 2: straddle and strangle

While delta spreads let you take advantage of static markets, buying a straddle or a strangle allows you to maximise your profit when the market is volatile. The more volatile it is and the more the market moves in one direction, the greater your profits can be.

### How to use a straddle

* A straddle involves simultaneously buying both a put and a call option on the same market, with the same strike price and expiry. By doing this you can profit from volatility, regardless of whether the underlying market moves up or down. But there is a risk - if no volatility occurs, you'll lose your premium.
* A straddle purchases puts and calls with the same strike price and time period.

<img width = 75% height = 75% src = "https://github.com/Louisli0515/Trading-Options-with-CFDs-IG-Academy/assets/128298224/acf257dd-bc35-413a-8d75-46b9beaf5936">

What about a short straddle?

* With a short straddle you can benefit if volatility collapses, by selling both the calls and puts. The strategy behind the short straddle is reaching a breakeven point where the underlying asset is either at the money (the strike price) or out of the money. This would be below the strike price for a call option but above the strike price for a put option. In either case, the option contract would expire worthless. The gain for you will be the profit you collect from the option premium.
* The risk in a short straddle strategy is unlimited, as the underlying asset price could move up or down well beyond the strike price of either option.

### Strangle

* A strangle is a similar strategy, but there you buy a call with a slightly higher strike price than the put. This means that you need a larger price move to profit, but you will typically pay less to open the trade because both options are purchased when out of the money.
* A strangle purchase involves puts and calls that are separated by at least one strike price in the same time period.

Long strangle

* Strangles can be either long or short.
* In a long strangle, you buy the calls and puts. The strategy is to profit if the underlying asset makes a move in either direction. You'd use a long strangle if you're expecting the underlying security to make significant price moves, such as in advace of an earnings announcement. Your profit potential is virtually unlimited, and your risk is limited to the option price you pay.

What about the risks vs the rewards?

* With a long strangle strategy, the maximum profit is unlimited because, theoretically, there is no limit to how high the underlying asset's value can rise. On the put side, the underlying price can only go to zero, capping your profit if it does so.
* However, your risk is limited to the option premium.

Short strangle

* In a short strangle, you are selling the calls and puts. You are predicting the underlying price will show little volatility, remaining somewhere between both strikes you select, so that the options you sell with expire worthless.
* The profit potential is limited to the net credit you earn from the premium you collect. But the risk is virtually unlimited because, in a worst-case scenario, you would be responsible for the options.

What about the risk?

* As the seller of the option, your maximum risk is virtually unlimited.
