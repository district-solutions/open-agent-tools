# Agent Python Tools

- repo: facebookresearch/spot-sim2real
- repo_uri: https://github.com/facebookresearch/spot-sim2real

## File: facebookresearch_spot-sim2real/ros_tcp/ros_communication_client/ros_communications.py

Prompts

```
['create a Publisher to advertise and publish ROS messages on a specified topic via rosbridge TCP', 'create a Subscriber to listen to a ROS topic and invoke a callback function on received messages', 'use StaticTransformBroadcaster to send static 3D transforms between parent and child frames on /tf_static', 'use TransformListener to subscribe to and receive static transform messages from the /tf_static topic', 'use Param to get and set ROS parameters via the rosapi set_param and get_param services', 'convert a numpy array to a ROS sensor_msgs/Image message with proper encoding and header', 'parse a ROS sensor_msgs/Image message into a numpy array with BGR color conversion', 'convert a 3D point and quaternion rotation to a ROS tf2_msgs/TFMessage with parent and child frames', 'parse a ROS tf2_msgs/TFMessage into a dictionary of 4x4 transformation matrices', 'convert a numpy float32 array to a ROS std_msgs/Float32MultiArray with dimension labels and stride', 'connect to a ROS bridge server using RosbridgeBSONTCPClient with host and port configuration', 'send a BSON-encoded dictionary message to the ROS bridge server via RosbridgeBSONTCPClient', 'receive and decode a BSON message from the ROS bridge server using recv_bson method', 'subscribe to a ROS topic with message type using RosbridgeJSONTCPClient subscribe method', 'call a ROS service like get_param using RosbridgeJSONTCPClient with callback handling']
```

Usage

```
{'create_Publisher': 'create a Publisher to advertise and publish ROS messages on a specified topic via rosbridge TCP', 'create_Subscriber': 'create a Subscriber to listen to a ROS topic and invoke a callback function on received messages', 'use_StaticTransformBroadcaster': 'use StaticTransformBroadcaster to send static 3D transforms between parent and child frames on /tf_static', 'use_TransformListener': 'use TransformListener to subscribe to and receive static transform messages from the /tf_static topic', 'use_Param': 'use Param to get and set ROS parameters via the rosapi set_param and get_param services'}
```

## File: facebookresearch_spot-sim2real/ros_tcp/ros_communication_client/ros_message_conveter.py

Prompts

```
['create a Publisher to advertise and publish ROS messages on a specified topic via rosbridge TCP', 'create a Subscriber to listen to a ROS topic and invoke a callback function on received messages', 'use StaticTransformBroadcaster to send static 3D transforms between parent and child frames on /tf_static', 'use TransformListener to subscribe to and receive static transform messages from the /tf_static topic', 'use Param to get and set ROS parameters via the rosapi set_param and get_param services', 'convert a numpy array to a ROS sensor_msgs/Image message with proper encoding and header', 'parse a ROS sensor_msgs/Image message into a numpy array with BGR color conversion', 'convert a 3D point and quaternion rotation to a ROS tf2_msgs/TFMessage with parent and child frames', 'parse a ROS tf2_msgs/TFMessage into a dictionary of 4x4 transformation matrices', 'convert a numpy float32 array to a ROS std_msgs/Float32MultiArray with dimension labels and stride', 'connect to a ROS bridge server using RosbridgeBSONTCPClient with host and port configuration', 'send a BSON-encoded dictionary message to the ROS bridge server via RosbridgeBSONTCPClient', 'receive and decode a BSON message from the ROS bridge server using recv_bson method', 'subscribe to a ROS topic with message type using RosbridgeJSONTCPClient subscribe method', 'call a ROS service like get_param using RosbridgeJSONTCPClient with callback handling']
```

Usage

```
{'convert_numpy_array_to_ros_image': 'convert a numpy array to a ROS sensor_msgs/Image message with proper encoding and header', 'parse_ros_image_to_numpy': 'parse a ROS sensor_msgs/Image message into a numpy array with BGR color conversion', 'convert_transforms_to_ros_tfmessage': 'convert a 3D point and quaternion rotation to a ROS tf2_msgs/TFMessage with parent and child frames', 'parse_ros_tfmessage_to_transforms': 'parse a ROS tf2_msgs/TFMessage into a dictionary of 4x4 transformation matrices', 'convert_numpy_array_to_ros_Float32MultiArray': 'convert a numpy float32 array to a ROS std_msgs/Float32MultiArray with dimension labels and stride'}
```

## File: facebookresearch_spot-sim2real/ros_tcp/ros_communication_client/ros_tcp.py

Prompts

```
['create a Publisher to advertise and publish ROS messages on a specified topic via rosbridge TCP', 'create a Subscriber to listen to a ROS topic and invoke a callback function on received messages', 'use StaticTransformBroadcaster to send static 3D transforms between parent and child frames on /tf_static', 'use TransformListener to subscribe to and receive static transform messages from the /tf_static topic', 'use Param to get and set ROS parameters via the rosapi set_param and get_param services', 'convert a numpy array to a ROS sensor_msgs/Image message with proper encoding and header', 'parse a ROS sensor_msgs/Image message into a numpy array with BGR color conversion', 'convert a 3D point and quaternion rotation to a ROS tf2_msgs/TFMessage with parent and child frames', 'parse a ROS tf2_msgs/TFMessage into a dictionary of 4x4 transformation matrices', 'convert a numpy float32 array to a ROS std_msgs/Float32MultiArray with dimension labels and stride', 'connect to a ROS bridge server using RosbridgeBSONTCPClient with host and port configuration', 'send a BSON-encoded dictionary message to the ROS bridge server via RosbridgeBSONTCPClient', 'receive and decode a BSON message from the ROS bridge server using recv_bson method', 'subscribe to a ROS topic with message type using RosbridgeJSONTCPClient subscribe method', 'call a ROS service like get_param using RosbridgeJSONTCPClient with callback handling']
```

Usage

```
{'connect_rosbridge_bson_client': 'connect to a ROS bridge server using RosbridgeBSONTCPClient with host and port configuration', 'send_bson_message': 'send a BSON-encoded dictionary message to the ROS bridge server via RosbridgeBSONTCPClient', 'receive_bson_message': 'receive and decode a BSON message from the ROS bridge server using recv_bson method', 'subscribe_ros_topic': 'subscribe to a ROS topic with message type using RosbridgeJSONTCPClient subscribe method', 'call_ros_service': 'call a ROS service like get_param using RosbridgeJSONTCPClient with callback handling'}
```

