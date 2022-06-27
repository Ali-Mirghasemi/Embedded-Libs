# Embedded Libs
This repository contains of multiple useful and most used library in embedded systems such as Microcontroller

## Stream
`Stream` Library help you to serialize and deserialize binary data over any communication protocol, such as UART, Ethernet, ...

#### Features
- Support Big-endian and Little-Endian
- Support serialize and deserialize all standard data types
- Memory safe for reading unaligned data
- `InputStream` and `OutputStream` can work over a HAL (Hardware Abstract Layer)
- User access to customize configuration base on hardware need
- Any bytes buffer can turn into `StreamBuffer` without zero copy

for more details see [Stream ReadMe](./Stream/README.md)

## Str
`Str` Library provide most used functions for work with strings in `C` language

#### Features
- Can work with or without `string.h` library
- Full set of function for convert data types into strings
- Full set of function for convert strings into data types
- Split functions
- Sort and Searching functions
- Finding functions
- Param parser

for more details see [Str ReadMe](./Str/README.md)

## Key
`Key` Library provide a key manager, such as Buttons and DipSwitch 

#### Features
- Support multiple key manager
- Support multiple key event (OnClick, OnPress, OnRelease, OnNone)
- Support Fixed array or linked list for key manager
- Each Key has own callbacks for each event
- Support multiple callbacks or single callback for each key
- Support customize key configuration based on hardware
- HAL (Hardware Abstract Layer) support

for more details see [Key ReadMe](./Key/README.md)

## CmdManager
`CmdManager` Library provide a command manager, such as CLI, Telnet, ... for your embedded system over a HAL (Hardware Abstract Layer)

#### Features
- Support multiple command manager
- Support multiple command event (Execute, Help, Set, Get, Response)
- Support custom command format
- Auto detect parameter type and convert it into data type
- Support multiple parameter for each command
- Support binary search or linear search
- Automatic sort command by name for more performance in searching
- Support customize command configuration based on hardware

for more details see [CmdManager ReadMe](./CmdManager/README.md)

## Codec
`Codec` Library help you to create your own layer protocol 

#### Features
- Support multiple codec
- Support Serialize and Deserialize data
- Support customize codec configuration based on hardware
- HAL (Hardware Abstract Layer) support

for more details see [Codec ReadMe](./Codec/README.md)

## Benchmark
`Benchmark` Library help you to benchmark your functions in embedded system

#### Features
- Support multiple benchmark
- Support customize benchmark configuration based on hardware
- HAL (Hardware Abstract Layer) support

for more details see [Benchmark ReadMe](./Benchmark/README.md)


