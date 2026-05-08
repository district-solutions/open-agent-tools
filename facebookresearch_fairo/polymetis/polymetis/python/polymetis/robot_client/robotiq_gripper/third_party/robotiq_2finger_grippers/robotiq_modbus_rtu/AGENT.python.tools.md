# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/polymetis/python/polymetis/robot_client/robotiq_gripper/third_party/robotiq_2finger_grippers/robotiq_modbus_rtu/comModbusRtu.py

Prompts

```
['connect to a Robotiq 2-finger gripper over Modbus RTU using a serial port device path', 'disconnect from a Robotiq 2-finger gripper by closing the Modbus RTU serial client connection', 'send a command to the Robotiq gripper by writing a list of uint8 bytes to Modbus register 0x03E8', 'read the Robotiq gripper status by reading holding registers starting at address 0x07D0 and returning bytes', 'review the communication class that wraps pymodbus ModbusSerialClient for Robotiq gripper RTU communication']
```

Usage

```
{'connect_robotiq_gripper': 'connect to a Robotiq 2-finger gripper over Modbus RTU using a serial port device path', 'disconnect_robotiq_gripper': 'disconnect from a Robotiq 2-finger gripper by closing the Modbus RTU serial client connection', 'send_gripper_command': 'send a command to the Robotiq gripper by writing a list of uint8 bytes to Modbus register 0x03E8', 'get_gripper_status': 'read the Robotiq gripper status by reading holding registers starting at address 0x07D0 and returning bytes', 'review_communication_class': 'review the communication class that wraps pymodbus ModbusSerialClient for Robotiq gripper RTU communication'}
```

