# Coffee vending machine

## Unit Tests

### Happy Path

- When I put money into the machine, I should see the amount inserted update
  and display the total amount I've put into the machine so far.
- When I press a button for coffee and the amount I've inserted is
  not enough to buy the coffee, the coffee's price should appear on the screen.
- When I have inserted more money than the coffeee costs, I should receive my change when coffee is dispensed.

### Unhappy Path

- When I insert money that is not correct currency, the machine should return the money immediately.
- When I insert a bill that is larger than a $5 bill, the machine should return the money immediately.
- If the machine is out of cups, an error message should be displayed and any money inserted be returned.
- When I press a button for coffee and the amount I've inserted is not enough
  to buy the coffee, the coffee's price should appear on the screen.
