UR1. I would like to see a list of dishes with prices__
UR2. I would like to be able to select some number of several available dishes__
UR3. I would like to check the total matches the sum of the various dishes__
UR4. I would like to receive a confirmation text__

Hints on functionality to implement:

Ensure you have a list of dishes with prices
Place the order by giving the list of dishes, their quantities and a number that should be the exact total. If the sum is not correct the method should raise an error, otherwise the customer is sent a text saying that the order was placed successfully and that it will be delivered 1 hour from now, e.g. "Thank you! Your order was placed and will be delivered before 18:52".
The text sending functionality should be implemented using Twilio API. You'll need to register for it. It’s free.
Use the twilio-ruby gem to access the API
Use the Gemfile to manage your gems
Make sure that your Takeaway is thoroughly tested and that you use mocks and/or stubs, as necessary to not to send texts when your tests are run
However, if your Takeaway is loaded into IRB and the order is placed, the text should actually be sent


Advanced:  Implement the ability to place orders via text message.  A free account on Twilio will only allow you to send texts to "verified" numbers. Use your mobile phone number, don't worry about the customer's mobile phone.