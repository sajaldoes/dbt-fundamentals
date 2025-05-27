{% docs order_status %}

Orders can be one of the following statuses:

| status         | description                                                               |
|----------------|---------------------------------------------------------------------------|
| placed         | The order has been placed but has not yet left the warehouse              |
| shipped        | The order has been shipped to the customer and is currently in transit    |
| completed      | The order has been received by the customer                               |
| retrun_pending | Customer has indicated the would like to return this item                 |
| returned       | The order has been returned by the customer and received at the warehouse |


{% enddocs %}