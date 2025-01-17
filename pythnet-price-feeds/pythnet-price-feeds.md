# Pythnet Price Feeds

Pythnet price feeds use an on-demand price update model, where users are responsible for posting price updates on-chain when needed.
Please see [_On-Demand Updates_](on-demand.md) to learn more about this model and what this means for integrators.

In the on-demand model, developers should integrate Pyth into both their on-chain and off-chain code:
1. On-chain programs should read prices from the Pyth program deployed on the same chain
2. Off-chain frontends and jobs should include Pyth price updates alongside (or within) their application-specific transactions.

Pyth provides ecosystem-specific SDKs to assist with both the on- and off-chain pieces of the integration.
The easiest way to use Pyth price feeds is to integrate the appropriate SDKs into your application.
Before getting started with an SDK, please read [_Using Price Feeds_](best-practices.md) to understand how Pyth price feeds are represented, and to learn best practices to use Pyth prices safely and correctly.
Then, follow the links below to find the right SDK for your ecosystem:

{% content-ref url="evm.md" %}
[evm.md](evm.md)
{% endcontent-ref %}

{% content-ref url="aptos.md" %}
[aptos.md](aptos.md)
{% endcontent-ref %}

{% content-ref url="bas.md" %}
[bas.md](bas.md)
{% endcontent-ref %}

{% content-ref url="cosmwasm.md" %}
[cosmwasm.md](cosmwasm.md)
{% endcontent-ref %}

{% content-ref url="off-chain.md" %}
[off-chain.md](off-chain.md)
{% endcontent-ref %}
