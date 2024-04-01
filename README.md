# HALF_SUBTRACTOR
# program
module half_subtractor(a,b,diff,borr);
input a,b;
output diff,borr;
wire x;
xor (diff,a,b);
not (x,a);
and (borr,x,b);
endmodule
Output
# Truth Table
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/d0d5980a-6bcf-4ede-a54e-6aae3fb5f5f2)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/df70da69-5a12-4a0d-ab84-a98dad3f7e70)
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/2f2d6a4d-9eda-4165-8579-1d7490b5fe97)
# output
![316440157-53f01ed9-dc08-46de-b943-28d1c32d2102](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/165644574/eccd41cc-18e9-4118-8aa4-ce65f2f7e960)
