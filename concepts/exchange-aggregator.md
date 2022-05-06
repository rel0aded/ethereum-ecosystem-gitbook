# Exchange Aggregator

Aggregators make use of multiple [decentralized exchanges](/concepts/decentralized-exchange.md) to determine which would provide the user with the best price for their swap between two assets. This includes determining which would charge the lowest fess and least slippage (change in price) to return the maximum number of tokens in the desired end currency.

In some cases, the system might determine that it needs to use multiple exchanges to achieve this result, but would only require the end-user to perform one transaction. This information will be displayed on the screen before the user confirms their transaction.

When only a single exchange is to be used, it is usually cheaper to use the associated application for those contracts directly, as using the aggregator will always require additional gas to be spent on processing, as it passes through the aggregator's code.
