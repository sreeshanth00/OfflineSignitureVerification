Offline signiture verfication system

The system is developed using a existing model which has been trained and tested on cerdar dataset(limited items).

![output 1](https://github.com/sreeshanth00/OfflineSignitureVerification/assets/94922151/cc1c25c6-9047-41b5-aca1-9a12203edc1e)
UI of Offline signiture verfication system


Enter Customer name, Upload 3 original signatures of the customer and click upload, The mean weight of these uploaded images are calculated on server and stored.

Now,Upload a new signature of the customer to verify.

The ouput is Generated, server calculates the weight of newly uploaded signiture, and compares with the existing mean weight of orignal sigitures.

If the Distance between "OrginalSigniture" and "NewSiguniture" is less than Threshhold Value, The Signiture is classified a Authentic

![output 3](https://github.com/sreeshanth00/OfflineSignitureVerification/assets/94922151/0b49a199-a6f8-4434-9556-4b349c36af46)

If Distance is more than Threshold value then image is classified as Forgery.

![output 2](https://github.com/sreeshanth00/OfflineSignitureVerification/assets/94922151/883f776b-112d-49e6-812a-093bb8bee9e3)
