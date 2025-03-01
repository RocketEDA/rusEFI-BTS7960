# BTS7960 Module Adapter

RusEFI's implementation of the H-bridge requires 3 pins, PWM, DIR, and EN. This is analogous to the TLE9201SG. On amazon and sorts, you can find these inexpensive 43A H bridge using the obsolete BTS7960. This project aims to create an adapter for them to work with rusEFI.

<img width="400" alt="image" src="https://github.com/user-attachments/assets/a7d1345f-8429-49de-a448-8d59349de8e0" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/18714690-9a89-40e7-ba40-8662f8ed9313" />

[source](https://www.ovaga.com/blog/transistor/bts7960-motor-driver-datasheet-and-circuit-diagram)

# Connection

The board stacks on as pictured. DIR/DIS/PWM correlate to rusEFI's 3/2 wire pins originally intended for the TLE9201SG. The DIS pin connection is not needed for 2 wire operation.

<img width="400" alt="image" src="https://github.com/user-attachments/assets/b0ed6dca-13c6-4856-b299-fb4f7ce63874" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/40c949d2-6db3-43ea-9580-4dfee241a7b8" />
