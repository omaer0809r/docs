[View code on GitHub](https://dune.com/docs/data-tables/community/reservoir/ask-events.md)

# Ask Events

This section of the app technical guide covers the `reservoir.ask_events` table, which contains records with information about each ask change. The table includes various columns such as `id`, `kind`, `contract`, `token_id`, `order_id`, `maker`, `price`, `quantity_remaining`, `valid_from`, `valid_until`, `source`, `tx_hash`, `tx_timestamp`, and `created_at`. 

The `id` column represents the internal event ID, while the `kind` column represents the type of event (e.g. new-order, expiry, sale, cancel, balance-change, approval-change, bootstrap, revalidation, reprice). The `contract` column contains the contract address, and the `token_id` column contains the ID of the token in the collection. The `order_id` column represents the associated ask ID, and the `maker` column contains the associated ask maker wallet address. The `price` column represents the associated ask price in native currency, and the `quantity_remaining` column represents the associated ask tokens remaining. The `valid_from` and `valid_until` columns represent the associated ask validity start and expiration, respectively. The `source` column contains the source of the order (e.g. opensea.io), while the `tx_hash` and `tx_timestamp` columns represent the associated transaction hash and timestamp, respectively. Finally, the `created_at` column represents the timestamp the event was recorded.

This section also includes query examples that can be found at the specified URLs. These queries can be used to retrieve information from the `reservoir.ask_events` table. 

Overall, this section of the app technical guide provides a detailed overview of the `reservoir.ask_events` table and its various columns. It also includes query examples that can be used to retrieve information from the table.
## Questions: 
 1. What is the purpose of the `reservoir.ask_events` table in the Dune Docs app?
- The `reservoir.ask_events` table contains records with information about each ask change in the app.

2. What are some examples of query options available for the `reservoir.ask_events` table?
- Query examples for the `reservoir.ask_events` table can be found at the following links: [https://dune.com/queries/1302858/2232178](https://dune.com/queries/1302858/2232178) and [https://dune.com/queries/1302863/2232189](https://dune.com/queries/1302863/2232189).

3. What types of events are included in the `kind` column of the `reservoir.ask_events` table?
- The `kind` column in the `reservoir.ask_events` table includes various event types such as new-order, expiry, sale, cancel, balance-change, approval-change, bootstrap, revalidation, and reprice.