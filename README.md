# Yellow Taxi Assignment


Given the circumstances of this assignment (purpose and capacity), this notebook provides a general overview of the Yellow Taxi data, highlighting key trends, rather than an in-depth examination of transactional data and a deep delve into each of its attributes.

---

A more detailed analysis would entail deeper understanding of features. 

Some examples are:

- `payment_type` (e.g. *in which cases is there “no charge”?* / *what does “dispute” mean in this context?*)
- `store_and_fwd_flag` (e.g *does “store and forward trip” mean that the registered dropoff time is not the real one due to lack of connection?*)
- `mta_tax` (e.g. *do entities/employers/self-employees pay different tax rates based on their supply?*)
- `airport_fee` (e.g. *the dictionary mentions pick up fee charged at LaGuardia airport, but such airport does not have an assigned `RateCodeID`*)

---

 ### Other cases for further analysis:
- explore relation between zones and number of passengers:
  - traffic
  - income level
  - ...
- exploring and dealing with other relevant missing values
