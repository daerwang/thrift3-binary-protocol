# thrift3-binary-protocol
Apache Thrift with modifications for compatibility with Python3, for use with the Babeltrace Zipkin plugins.

This library simply uses BytesIO instead of StringIO and the Python3 buffer interface, in the Transport and BinaryProtocol classes.

