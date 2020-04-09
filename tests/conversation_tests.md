## Story from conversation with 359c5cd8-0358-45e3-b3a0-5de141100efa on April 9th 2020

* greet: hi
    - utter_greet
* pay_cc: when is my next bill due?
    - action_default_fallback
* pay_cc: when is my payment due?
    - cc_payment_form
    - form{"name":"cc_payment_form"}
    - slot{"requested_slot":"credit_card"}
* transfer_money: can I speak to a person?
    - action_default_fallback
* search_transactions: speak to human
    - action_default_fallback
