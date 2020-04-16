# BACnet Server Example CPP

A basic BACnet IP server example written with C++ using the [CAS BACnet Stack](https://www.bacnetstack.com/).

- Device: 389999 (Device Rainbow)
  - analog_input: 0  (AnalogInput Bronze)
  - analog_output: 1  (AnalogOutput Chartreuse)
  - analog_value: 2  (AnalogValue Diamond)
  - binary_input: 3  (BinaryInput Emerald)
  - binary_output: 4  (BinaryOutput Fuchsia)
  - binary_value: 5  (BinaryValue Gold)
  - multi_state_input: 13  (MultiStateInput Hot Pink)
  - multi_state_output: 14  (MultiStateOutput Indigo)
  - multi_state_value: 19  (MultiStateValue Kiwi)
  - trend_log: 20  (TrendLog Lilac)
  - trend_log_multiple: 27  (TrendLogMultiple Magenta)
  - bitstring_value: 39  (BitstringValue Nickel)
  - characterstring_value: 40  (CharacterstringValue Onyx)
  - data_value: 42  (DateValue Purple)
  - integer_value: 45  (IntegerValue Quartz)
  - large_analog_value: 46  (LargeAnalogValue Red)
  - octetstring_value: 47  (OctetstringValue Silver)
  - positive_integer_value: 48  (PositiveIntegerValue Turquoise)
  - time_value: 50  (TimeValue Umber)
  - NetworkPort: 56  (NetworkPort Vermilion)

## Building

A [Visual studio 2019](https://visualstudio.microsoft.com/downloads/) project is included with this project.

This project also auto built using [Gitlab CI](https://docs.gitlab.com/ee/ci/) on every commit.

## Releases

Build versions of this example can be downloaded from the releases page: 

[https://github.com/chipkin/BACnetServerExampleCPP/releases](https://github.com/chipkin/BACnetServerExampleCPP/releases)
