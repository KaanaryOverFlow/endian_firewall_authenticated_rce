# endian_firewall_authenticated_rce

Endinan Firewall Community version 3.3.2 authenticated remote code execution as nobody.

when i was start create backup, output of ps command is be interesting.

![dikkatcekennokta](https://user-images.githubusercontent.com/29048982/107676349-17889800-6caa-11eb-88a1-172c0180ba40.png)

and checking the input is validated ?

![create-file](https://user-images.githubusercontent.com/29048982/107676611-62a2ab00-6caa-11eb-949e-b1c42f61741e.png)

no. we can run command.check the permission.

![permission](https://user-images.githubusercontent.com/29048982/107676786-97166700-6caa-11eb-85be-fb8d3bd0acfc.png)

we can run command as nobody.



1-) login in web application.

2-) create backup and select any options and write payload to comment. eg. aaaa$(id)bbbb

3-) start to backup.


                                                         Proof Of Concept


![endian_poc](https://user-images.githubusercontent.com/29048982/107675418-2589e900-6ca9-11eb-870d-447daded3575.gif)
