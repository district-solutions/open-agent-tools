# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/examples/python/route_guide/route_guide_client.py

Prompts

```
['run the gRPC route guide client to exercise all four RPC types against localhost:50051', 'call GetFeature RPC to look up a named feature at a given latitude and longitude point', 'call ListFeatures RPC to retrieve all features within a rectangular geographic bounding box', 'call RecordRoute RPC to stream random route points and receive a trip summary with distance and time', 'call RouteChat RPC to send bidirectional route notes and receive matching messages from the server', 'create a RouteGuideStub client using a gRPC channel to call unary and streaming RPC methods', 'implement the GetFeature method in RouteGuideServicer to return a feature at a given Point position', 'implement the ListFeatures method in RouteGuideServicer to stream features within a Rectangle area', 'implement the RecordRoute method in RouteGuideServicer to accept a stream of Points and return a RouteSummary', 'register a RouteGuideServicer instance to a gRPC server using add_RouteGuideServicer_to_server', 'read the route guide database JSON file and return a list of protobuf Feature objects', 'review the read_route_guide_database function to understand how it parses route_guide_db.json into protobuf Features', 'refactor read_route_guide_database to accept a file path argument instead of hardcoding route_guide_db.json', 'test the read_route_guide_database function by calling it and verifying the returned Feature list', 'summarize the read_route_guide_database function which loads geographic features from a JSON database file', 'run the gRPC route guide server on port 50051 with a thread pool of 10 workers', 'create a function that looks up a Feature by location point in a feature database', 'create a function that calculates the great circle distance in meters between two lat/lon points', 'review the RouteGuideServicer ListFeatures method that streams features within a rectangular bounding box', 'review the RouteGuideServicer RecordRoute method that streams points and returns a route summary with distance and time']
```

Usage

```
{'run_route_guide_client': 'run the gRPC route guide client to exercise all four RPC types against localhost:50051', 'guide_get_feature': 'call GetFeature RPC to look up a named feature at a given latitude and longitude point', 'guide_list_features': 'call ListFeatures RPC to retrieve all features within a rectangular geographic bounding box', 'guide_record_route': 'call RecordRoute RPC to stream random route points and receive a trip summary with distance and time', 'guide_route_chat': 'call RouteChat RPC to send bidirectional route notes and receive matching messages from the server'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/examples/python/route_guide/route_guide_pb2_grpc.py

Prompts

```
['run the gRPC route guide client to exercise all four RPC types against localhost:50051', 'call GetFeature RPC to look up a named feature at a given latitude and longitude point', 'call ListFeatures RPC to retrieve all features within a rectangular geographic bounding box', 'call RecordRoute RPC to stream random route points and receive a trip summary with distance and time', 'call RouteChat RPC to send bidirectional route notes and receive matching messages from the server', 'create a RouteGuideStub client using a gRPC channel to call unary and streaming RPC methods', 'implement the GetFeature method in RouteGuideServicer to return a feature at a given Point position', 'implement the ListFeatures method in RouteGuideServicer to stream features within a Rectangle area', 'implement the RecordRoute method in RouteGuideServicer to accept a stream of Points and return a RouteSummary', 'register a RouteGuideServicer instance to a gRPC server using add_RouteGuideServicer_to_server', 'read the route guide database JSON file and return a list of protobuf Feature objects', 'review the read_route_guide_database function to understand how it parses route_guide_db.json into protobuf Features', 'refactor read_route_guide_database to accept a file path argument instead of hardcoding route_guide_db.json', 'test the read_route_guide_database function by calling it and verifying the returned Feature list', 'summarize the read_route_guide_database function which loads geographic features from a JSON database file', 'run the gRPC route guide server on port 50051 with a thread pool of 10 workers', 'create a function that looks up a Feature by location point in a feature database', 'create a function that calculates the great circle distance in meters between two lat/lon points', 'review the RouteGuideServicer ListFeatures method that streams features within a rectangular bounding box', 'review the RouteGuideServicer RecordRoute method that streams points and returns a route summary with distance and time']
```

Usage

```
{'create_RouteGuideStub': 'create a RouteGuideStub client using a gRPC channel to call unary and streaming RPC methods', 'implement_RouteGuideServicer_GetFeature': 'implement the GetFeature method in RouteGuideServicer to return a feature at a given Point position', 'implement_RouteGuideServicer_ListFeatures': 'implement the ListFeatures method in RouteGuideServicer to stream features within a Rectangle area', 'implement_RouteGuideServicer_RecordRoute': 'implement the RecordRoute method in RouteGuideServicer to accept a stream of Points and return a RouteSummary', 'register_RouteGuideServicer': 'register a RouteGuideServicer instance to a gRPC server using add_RouteGuideServicer_to_server'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/examples/python/route_guide/route_guide_resources.py

Prompts

```
['run the gRPC route guide client to exercise all four RPC types against localhost:50051', 'call GetFeature RPC to look up a named feature at a given latitude and longitude point', 'call ListFeatures RPC to retrieve all features within a rectangular geographic bounding box', 'call RecordRoute RPC to stream random route points and receive a trip summary with distance and time', 'call RouteChat RPC to send bidirectional route notes and receive matching messages from the server', 'create a RouteGuideStub client using a gRPC channel to call unary and streaming RPC methods', 'implement the GetFeature method in RouteGuideServicer to return a feature at a given Point position', 'implement the ListFeatures method in RouteGuideServicer to stream features within a Rectangle area', 'implement the RecordRoute method in RouteGuideServicer to accept a stream of Points and return a RouteSummary', 'register a RouteGuideServicer instance to a gRPC server using add_RouteGuideServicer_to_server', 'read the route guide database JSON file and return a list of protobuf Feature objects', 'review the read_route_guide_database function to understand how it parses route_guide_db.json into protobuf Features', 'refactor read_route_guide_database to accept a file path argument instead of hardcoding route_guide_db.json', 'test the read_route_guide_database function by calling it and verifying the returned Feature list', 'summarize the read_route_guide_database function which loads geographic features from a JSON database file', 'run the gRPC route guide server on port 50051 with a thread pool of 10 workers', 'create a function that looks up a Feature by location point in a feature database', 'create a function that calculates the great circle distance in meters between two lat/lon points', 'review the RouteGuideServicer ListFeatures method that streams features within a rectangular bounding box', 'review the RouteGuideServicer RecordRoute method that streams points and returns a route summary with distance and time']
```

Usage

```
{'read_route_guide_database': 'read the route guide database JSON file and return a list of protobuf Feature objects', 'review_read_route_guide_database': 'review the read_route_guide_database function to understand how it parses route_guide_db.json into protobuf Features', 'refactor_read_route_guide_database': 'refactor read_route_guide_database to accept a file path argument instead of hardcoding route_guide_db.json', 'test_read_route_guide_database': 'test the read_route_guide_database function by calling it and verifying the returned Feature list', 'summarize_read_route_guide_database': 'summarize the read_route_guide_database function which loads geographic features from a JSON database file'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/examples/python/route_guide/route_guide_server.py

Prompts

```
['run the gRPC route guide client to exercise all four RPC types against localhost:50051', 'call GetFeature RPC to look up a named feature at a given latitude and longitude point', 'call ListFeatures RPC to retrieve all features within a rectangular geographic bounding box', 'call RecordRoute RPC to stream random route points and receive a trip summary with distance and time', 'call RouteChat RPC to send bidirectional route notes and receive matching messages from the server', 'create a RouteGuideStub client using a gRPC channel to call unary and streaming RPC methods', 'implement the GetFeature method in RouteGuideServicer to return a feature at a given Point position', 'implement the ListFeatures method in RouteGuideServicer to stream features within a Rectangle area', 'implement the RecordRoute method in RouteGuideServicer to accept a stream of Points and return a RouteSummary', 'register a RouteGuideServicer instance to a gRPC server using add_RouteGuideServicer_to_server', 'read the route guide database JSON file and return a list of protobuf Feature objects', 'review the read_route_guide_database function to understand how it parses route_guide_db.json into protobuf Features', 'refactor read_route_guide_database to accept a file path argument instead of hardcoding route_guide_db.json', 'test the read_route_guide_database function by calling it and verifying the returned Feature list', 'summarize the read_route_guide_database function which loads geographic features from a JSON database file', 'run the gRPC route guide server on port 50051 with a thread pool of 10 workers', 'create a function that looks up a Feature by location point in a feature database', 'create a function that calculates the great circle distance in meters between two lat/lon points', 'review the RouteGuideServicer ListFeatures method that streams features within a rectangular bounding box', 'review the RouteGuideServicer RecordRoute method that streams points and returns a route summary with distance and time']
```

Usage

```
{'run_route_guide_server': 'run the gRPC route guide server on port 50051 with a thread pool of 10 workers', 'create_get_feature': 'create a function that looks up a Feature by location point in a feature database', 'create_get_distance': 'create a function that calculates the great circle distance in meters between two lat/lon points', 'review_RouteGuideServicer_ListFeatures': 'review the RouteGuideServicer ListFeatures method that streams features within a rectangular bounding box', 'review_RouteGuideServicer_RecordRoute': 'review the RouteGuideServicer RecordRoute method that streams points and returns a route summary with distance and time'}
```

