This subproject contains POJOs from which PDP request and response JSON can be serialized and deserialized.
Models include annotations for Jackson, to override defaults provided by Jackson's ObjectMapper. Additionally,
models contain OpenAPI (fka Swagger) annotations to allow consuming applications to generate OpenAPI specifications
from code.

See example code in [`examples`](../examples/src/main/java/io/xacml/pep/json/AuthZClientExamples.java) subproject