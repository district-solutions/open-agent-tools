# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/examples/python/route_guide/route_guide_client.py

Prompts

```
['run the gRPC route guide client to test all four RPC types against localhost:50051', 'use the gRPC stub to fetch a single feature by its latitude and longitude coordinates', 'query the gRPC server for all features within a rectangular geographic bounding box', 'stream random route points to the gRPC server and receive a trip summary with distance', 'send bidirectional streaming RouteNote messages to the gRPC server and print received responses', 'create a RouteGuideStub instance with a gRPC channel to call unary and streaming RPCs', 'implement a RouteGuideServicer subclass to handle GetFeature, ListFeatures, RecordRoute, and RouteChat RPCs', 'call add_RouteGuideServicer_to_server to register a servicer instance on a gRPC server', 'review the RouteGuideStub class to understand unary_unary, unary_stream, stream_unary, and stream_stream RPC bindings', 'refactor the RouteGuideServicer methods to implement actual route guide logic instead of raising NotImplementedError', 'read the route guide database JSON file and return a list of Feature protobuf objects', 'run the route guide resources module to load features from route_guide_db.json into memory', 'review the read_route_guide_database function that parses JSON into route_guide_pb2.Feature objects', 'summarize the read_route_guide_database function which loads geographic features from a JSON database file', 'test the read_route_guide_database function to verify it correctly parses route_guide_db.json into Feature objects', 'run the gRPC route guide server on port 50051 with a thread pool of 10 workers', 'review the RouteGuideServicer GetFeature method that looks up a feature by location point', 'review the RouteGuideServicer ListFeatures method that yields features within a rectangular bounding box', 'review the RouteGuideServicer RecordRoute method that streams points and returns a route summary with distance and time', 'review the RouteGuideServicer RouteChat method that echoes back notes sent to the same location']
```

Usage

```
{'run_route_guide_client': 'run the gRPC route guide client to test all four RPC types against localhost:50051', 'guide_get_feature': 'use the gRPC stub to fetch a single feature by its latitude and longitude coordinates', 'guide_list_features': 'query the gRPC server for all features within a rectangular geographic bounding box', 'guide_record_route': 'stream random route points to the gRPC server and receive a trip summary with distance', 'guide_route_chat': 'send bidirectional streaming RouteNote messages to the gRPC server and print received responses'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/examples/python/route_guide/route_guide_pb2_grpc.py

Prompts

```
['run the gRPC route guide client to test all four RPC types against localhost:50051', 'use the gRPC stub to fetch a single feature by its latitude and longitude coordinates', 'query the gRPC server for all features within a rectangular geographic bounding box', 'stream random route points to the gRPC server and receive a trip summary with distance', 'send bidirectional streaming RouteNote messages to the gRPC server and print received responses', 'create a RouteGuideStub instance with a gRPC channel to call unary and streaming RPCs', 'implement a RouteGuideServicer subclass to handle GetFeature, ListFeatures, RecordRoute, and RouteChat RPCs', 'call add_RouteGuideServicer_to_server to register a servicer instance on a gRPC server', 'review the RouteGuideStub class to understand unary_unary, unary_stream, stream_unary, and stream_stream RPC bindings', 'refactor the RouteGuideServicer methods to implement actual route guide logic instead of raising NotImplementedError', 'read the route guide database JSON file and return a list of Feature protobuf objects', 'run the route guide resources module to load features from route_guide_db.json into memory', 'review the read_route_guide_database function that parses JSON into route_guide_pb2.Feature objects', 'summarize the read_route_guide_database function which loads geographic features from a JSON database file', 'test the read_route_guide_database function to verify it correctly parses route_guide_db.json into Feature objects', 'run the gRPC route guide server on port 50051 with a thread pool of 10 workers', 'review the RouteGuideServicer GetFeature method that looks up a feature by location point', 'review the RouteGuideServicer ListFeatures method that yields features within a rectangular bounding box', 'review the RouteGuideServicer RecordRoute method that streams points and returns a route summary with distance and time', 'review the RouteGuideServicer RouteChat method that echoes back notes sent to the same location']
```

Usage

```
{'create_stub_for_routeguide_client': 'create a RouteGuideStub instance with a gRPC channel to call unary and streaming RPCs', 'implement_routeguide_servicer': 'implement a RouteGuideServicer subclass to handle GetFeature, ListFeatures, RecordRoute, and RouteChat RPCs', 'register_servicer_on_server': 'call add_RouteGuideServicer_to_server to register a servicer instance on a gRPC server', 'review_routeguide_stub_methods': 'review the RouteGuideStub class to understand unary_unary, unary_stream, stream_unary, and stream_stream RPC bindings', 'refactor_servicer_methods': 'refactor the RouteGuideServicer methods to implement actual route guide logic instead of raising NotImplementedError'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/examples/python/route_guide/route_guide_resources.py

Prompts

```
['run the gRPC route guide client to test all four RPC types against localhost:50051', 'use the gRPC stub to fetch a single feature by its latitude and longitude coordinates', 'query the gRPC server for all features within a rectangular geographic bounding box', 'stream random route points to the gRPC server and receive a trip summary with distance', 'send bidirectional streaming RouteNote messages to the gRPC server and print received responses', 'create a RouteGuideStub instance with a gRPC channel to call unary and streaming RPCs', 'implement a RouteGuideServicer subclass to handle GetFeature, ListFeatures, RecordRoute, and RouteChat RPCs', 'call add_RouteGuideServicer_to_server to register a servicer instance on a gRPC server', 'review the RouteGuideStub class to understand unary_unary, unary_stream, stream_unary, and stream_stream RPC bindings', 'refactor the RouteGuideServicer methods to implement actual route guide logic instead of raising NotImplementedError', 'read the route guide database JSON file and return a list of Feature protobuf objects', 'run the route guide resources module to load features from route_guide_db.json into memory', 'review the read_route_guide_database function that parses JSON into route_guide_pb2.Feature objects', 'summarize the read_route_guide_database function which loads geographic features from a JSON database file', 'test the read_route_guide_database function to verify it correctly parses route_guide_db.json into Feature objects', 'run the gRPC route guide server on port 50051 with a thread pool of 10 workers', 'review the RouteGuideServicer GetFeature method that looks up a feature by location point', 'review the RouteGuideServicer ListFeatures method that yields features within a rectangular bounding box', 'review the RouteGuideServicer RecordRoute method that streams points and returns a route summary with distance and time', 'review the RouteGuideServicer RouteChat method that echoes back notes sent to the same location']
```

Usage

```
{'read_route_guide_database': 'read the route guide database JSON file and return a list of Feature protobuf objects', 'run_route_guide_resources': 'run the route guide resources module to load features from route_guide_db.json into memory', 'review_read_route_guide_database': 'review the read_route_guide_database function that parses JSON into route_guide_pb2.Feature objects', 'summarize_read_route_guide_database': 'summarize the read_route_guide_database function which loads geographic features from a JSON database file', 'test_read_route_guide_database': 'test the read_route_guide_database function to verify it correctly parses route_guide_db.json into Feature objects'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/examples/python/route_guide/route_guide_server.py

Prompts

```
['run the gRPC route guide client to test all four RPC types against localhost:50051', 'use the gRPC stub to fetch a single feature by its latitude and longitude coordinates', 'query the gRPC server for all features within a rectangular geographic bounding box', 'stream random route points to the gRPC server and receive a trip summary with distance', 'send bidirectional streaming RouteNote messages to the gRPC server and print received responses', 'create a RouteGuideStub instance with a gRPC channel to call unary and streaming RPCs', 'implement a RouteGuideServicer subclass to handle GetFeature, ListFeatures, RecordRoute, and RouteChat RPCs', 'call add_RouteGuideServicer_to_server to register a servicer instance on a gRPC server', 'review the RouteGuideStub class to understand unary_unary, unary_stream, stream_unary, and stream_stream RPC bindings', 'refactor the RouteGuideServicer methods to implement actual route guide logic instead of raising NotImplementedError', 'read the route guide database JSON file and return a list of Feature protobuf objects', 'run the route guide resources module to load features from route_guide_db.json into memory', 'review the read_route_guide_database function that parses JSON into route_guide_pb2.Feature objects', 'summarize the read_route_guide_database function which loads geographic features from a JSON database file', 'test the read_route_guide_database function to verify it correctly parses route_guide_db.json into Feature objects', 'run the gRPC route guide server on port 50051 with a thread pool of 10 workers', 'review the RouteGuideServicer GetFeature method that looks up a feature by location point', 'review the RouteGuideServicer ListFeatures method that yields features within a rectangular bounding box', 'review the RouteGuideServicer RecordRoute method that streams points and returns a route summary with distance and time', 'review the RouteGuideServicer RouteChat method that echoes back notes sent to the same location']
```

Usage

```
{'run_grpc_route_guide_server': 'run the gRPC route guide server on port 50051 with a thread pool of 10 workers', 'review_RouteGuideServicer_GetFeature': 'review the RouteGuideServicer GetFeature method that looks up a feature by location point', 'review_RouteGuideServicer_ListFeatures': 'review the RouteGuideServicer ListFeatures method that yields features within a rectangular bounding box', 'review_RouteGuideServicer_RecordRoute': 'review the RouteGuideServicer RecordRoute method that streams points and returns a route summary with distance and time', 'review_RouteGuideServicer_RouteChat': 'review the RouteGuideServicer RouteChat method that echoes back notes sent to the same location'}
```

