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
