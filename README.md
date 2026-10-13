# Electronics Purchase Funnel

An independent data analytics case study using public electronics-store events from REES46 / Open CDP, shared through Kaggle.

## Read the project

- [Full case study (PDF)](case-study/electronics-purchase-funnel.pdf)
- [Observed funnel chart](assets/observed-funnel.png)

The analysis studies the observed `view → cart → purchase` journey for the same product within a session. It uses Python and SQLite, distinguishes event counts from product-session cohorts, and considers repeated events, missing category labels, and incomplete observed purchase chains.

The source file covers 24 September 2020 to 28 February 2021. Its 885,129 events yield a strict-sequence funnel of 631,353 viewed product-session pairs, 48,896 carted pairs, and 22,920 purchased pairs. These figures describe observed behavior; they are not unique people, orders, or evidence of a causal revenue uplift.

Only the aggregate report and chart are published here. Raw events and user/session identifiers are excluded.

Source: [Kaggle electronics events dataset](https://www.kaggle.com/datasets/mkechinov/ecommerce-events-history-in-electronics-store).
