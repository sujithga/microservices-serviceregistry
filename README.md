This project explains how how Service Registry & Api-Gateway works
- Created Employee-Service. (Consider this as micro service)
- Created another project Employee-Serice2 exact same as Employee-Service.  This is just to give the. feeling of 2 instances of Employee-Service.  Though in realworld 2 instances of Employee-Service will be there.
- Create EurekaServer where Employee-Service & Employee-Service2 will be registered
- Create Api-Gateway project which exposes Employee-Service to outside world
- Register Api-Gateway also with Eurek server
