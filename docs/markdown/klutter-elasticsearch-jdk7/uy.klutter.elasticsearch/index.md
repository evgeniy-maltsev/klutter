[uy.klutter.elasticsearch](.)


## Package uy.klutter.elasticsearch

### Types

|&nbsp;|&nbsp;|
|---|---|
| [EsConfig](-es-config/index.md) | `object EsConfig` |
| [EsIndexedField](-es-indexed-field/index.md) | `enum class EsIndexedField` |
| [EsStoredField](-es-stored-field/index.md) | `enum class EsStoredField` |
| [EsSystemFields](-es-system-fields/index.md) | `enum class EsSystemFields` |
| [IndexTypeMapping](-index-type-mapping/index.md) | `data class IndexTypeMapping` |
| [XContentJsonArray](-x-content-json-array/index.md) | `class XContentJsonArray` |
| [XContentJsonObject](-x-content-json-object/index.md) | `open class XContentJsonObject` |
| [XContentJsonObjectWithClass](-x-content-json-object-with-class/index.md) | `class XContentJsonObjectWithClass<T&nbsp;:&nbsp;Any>&nbsp;:&nbsp;[XContentJsonObject](-x-content-json-object/index.md)` |
| [XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md) | `class XContentJsonObjectWithEnum<T&nbsp;:&nbsp;Enum<T>>&nbsp;:&nbsp;[XContentJsonObject](-x-content-json-object/index.md)` |

### Exceptions

|&nbsp;|&nbsp;|
|---|---|
| [WrappedThrowableException](-wrapped-throwable-exception/index.md) | `class WrappedThrowableException&nbsp;:&nbsp;[Exception](http://docs.oracle.com/javase/6/docs/api/java/lang/Exception.html)` |

### Extensions for External Classes

|&nbsp;|&nbsp;|
|---|---|
| [org.elasticsearch.action.ActionRequestBuilder](org.elasticsearch.action.-action-request-builder/index.md) |  |
| [org.elasticsearch.action.index.IndexRequestBuilder](org.elasticsearch.action.index.-index-request-builder/index.md) |  |
| [org.elasticsearch.action.search.SearchResponse](org.elasticsearch.action.search.-search-response/index.md) |  |
| [org.elasticsearch.client.Client](org.elasticsearch.client.-client/index.md) |  |
| [org.elasticsearch.search.SearchHits](org.elasticsearch.search.-search-hits/index.md) |  |

### Functions

|&nbsp;|&nbsp;|
|---|---|
| [booleanField](boolean-field.md) | `fun <T&nbsp;:&nbsp;Enum<T>> [XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<T>.~~booleanField~~(field:&nbsp;T, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit` |
| [booleanFieldMapping](boolean-field-mapping.md) | `fun <T&nbsp;:&nbsp;Enum<T>> [XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<T>.booleanFieldMapping(field:&nbsp;T, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit`
`fun <T&nbsp;:&nbsp;Any> [XContentJsonObjectWithClass](-x-content-json-object-with-class/index.md)<T>.booleanFieldMapping(field:&nbsp;KProperty1<T,&nbsp;*>, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit`
`fun [XContentJsonObject](-x-content-json-object/index.md).booleanFieldMapping(field:&nbsp;String, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit` |
| [dateField](date-field.md) | `fun <T&nbsp;:&nbsp;Enum<T>> [XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<T>.~~dateField~~(field:&nbsp;T, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit` |
| [dateFieldMapping](date-field-mapping.md) | `fun <T&nbsp;:&nbsp;Enum<T>> [XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<T>.dateFieldMapping(field:&nbsp;T, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit`
`fun <T&nbsp;:&nbsp;Any> [XContentJsonObjectWithClass](-x-content-json-object-with-class/index.md)<T>.dateFieldMapping(field:&nbsp;KProperty1<T,&nbsp;*>, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit`
`fun [XContentJsonObject](-x-content-json-object/index.md).dateFieldMapping(field:&nbsp;String, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit` |
| [esEmbeddedClient](es-embedded-client.md) | `fun esEmbeddedClient(clusterName:&nbsp;String, baseDir:&nbsp;[Path](http://docs.oracle.com/javase/6/docs/api/java/nio/file/Path.html), settings:&nbsp;Map<String,&nbsp;String>): Promise<Client,&nbsp;[Exception](http://docs.oracle.com/javase/6/docs/api/java/lang/Exception.html)>`
`fun esEmbeddedClient(clusterName:&nbsp;String, baseDir:&nbsp;[Path](http://docs.oracle.com/javase/6/docs/api/java/nio/file/Path.html), init:&nbsp;Builder.()&nbsp;->&nbsp;Unit): Promise<Client,&nbsp;[Exception](http://docs.oracle.com/javase/6/docs/api/java/lang/Exception.html)>` |
| [esNodeClient](es-node-client.md) | `fun esNodeClient(clusterName:&nbsp;String, settings:&nbsp;Map<String,&nbsp;String>): Client`
`fun esNodeClient(clusterName:&nbsp;String, init:&nbsp;Builder.()&nbsp;->&nbsp;Unit): Client` |
| [esTransportClient](es-transport-client.md) | `fun esTransportClient(clusterName:&nbsp;String, nodes:&nbsp;List<TransportAddress>, settings:&nbsp;Map<String,&nbsp;String>): Client`
`fun esTransportClient(clusterName:&nbsp;String, nodes:&nbsp;List<TransportAddress>, init:&nbsp;Builder.()&nbsp;->&nbsp;Unit): Client` |
| [ignoreField](ignore-field.md) | `fun <T&nbsp;:&nbsp;Enum<T>> [XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<T>.~~ignoreField~~(field:&nbsp;T): Unit` |
| [ignoreFieldMapping](ignore-field-mapping.md) | `fun <T&nbsp;:&nbsp;Enum<T>> [XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<T>.ignoreFieldMapping(field:&nbsp;T): Unit`
`fun <T&nbsp;:&nbsp;Any> [XContentJsonObjectWithClass](-x-content-json-object-with-class/index.md)<T>.ignoreFieldMapping(field:&nbsp;KProperty1<T,&nbsp;*>): Unit`
`fun [XContentJsonObject](-x-content-json-object/index.md).ignoreFieldMapping(field:&nbsp;String): Unit` |
| [integerField](integer-field.md) | `fun <T&nbsp;:&nbsp;Enum<T>> [XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<T>.~~integerField~~(field:&nbsp;T, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit` |
| [integerFieldMapping](integer-field-mapping.md) | `fun <T&nbsp;:&nbsp;Enum<T>> [XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<T>.integerFieldMapping(field:&nbsp;T, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit`
`fun <T&nbsp;:&nbsp;Any> [XContentJsonObjectWithClass](-x-content-json-object-with-class/index.md)<T>.integerFieldMapping(field:&nbsp;KProperty1<T,&nbsp;*>, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit`
`fun [XContentJsonObject](-x-content-json-object/index.md).integerFieldMapping(field:&nbsp;String, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit): Unit` |
| [longField](long-field.md) | `fun <T&nbsp;:&nbsp;Enum<T>> [XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<T>.~~longField~~(field:&nbsp;T, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit` |
| [longFieldMapping](long-field-mapping.md) | `fun <T&nbsp;:&nbsp;Enum<T>> [XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<T>.longFieldMapping(field:&nbsp;T, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit`
`fun <T&nbsp;:&nbsp;Any> [XContentJsonObjectWithClass](-x-content-json-object-with-class/index.md)<T>.longFieldMapping(field:&nbsp;KProperty1<T,&nbsp;*>, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit`
`fun [XContentJsonObject](-x-content-json-object/index.md).longFieldMapping(field:&nbsp;String, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit): Unit` |
| [mappingsForType](mappings-for-type.md) | `fun mappingsForType(type:&nbsp;String, allowDynamic:&nbsp;Boolean&nbsp;=&nbsp;false, initTopLevel:&nbsp;[XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<[EsSystemFields](-es-system-fields/index.md)>.()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}, initProperties:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit): [IndexTypeMapping](-index-type-mapping/index.md)` |
| [mappingsForTypeForClass](mappings-for-type-for-class.md) | `fun <T&nbsp;:&nbsp;Any> ~~mappingsForTypeForClass~~(type:&nbsp;String, allowDynamic:&nbsp;Boolean&nbsp;=&nbsp;false, initTopLevel:&nbsp;[XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<[EsSystemFields](-es-system-fields/index.md)>.()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}, initProperties:&nbsp;[XContentJsonObjectWithClass](-x-content-json-object-with-class/index.md)<T>.()&nbsp;->&nbsp;Unit): [IndexTypeMapping](-index-type-mapping/index.md)` |
| [mappingsForTypeWithClass](mappings-for-type-with-class.md) | `fun <T&nbsp;:&nbsp;Any> mappingsForTypeWithClass(type:&nbsp;String, allowDynamic:&nbsp;Boolean&nbsp;=&nbsp;false, initTopLevel:&nbsp;[XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<[EsSystemFields](-es-system-fields/index.md)>.()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}, initProperties:&nbsp;[XContentJsonObjectWithClass](-x-content-json-object-with-class/index.md)<T>.()&nbsp;->&nbsp;Unit): [IndexTypeMapping](-index-type-mapping/index.md)` |
| [mappingsForTypeWithEnum](mappings-for-type-with-enum.md) | `fun <T&nbsp;:&nbsp;Enum<T>> mappingsForTypeWithEnum(type:&nbsp;String, allowDynamic:&nbsp;Boolean&nbsp;=&nbsp;false, initTopLevel:&nbsp;[XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<[EsSystemFields](-es-system-fields/index.md)>.()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}, initProperties:&nbsp;[XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<T>.()&nbsp;->&nbsp;Unit): [IndexTypeMapping](-index-type-mapping/index.md)` |
| [promiseResult](promise-result.md) | `fun <T&nbsp;:&nbsp;Any> promiseResult(deferred:&nbsp;Deferred<T,&nbsp;[Exception](http://docs.oracle.com/javase/6/docs/api/java/lang/Exception.html)>): ActionListener<T>`
`fun <T&nbsp;:&nbsp;Any, O&nbsp;:&nbsp;Any> promiseResult(deferred:&nbsp;Deferred<T,&nbsp;[Exception](http://docs.oracle.com/javase/6/docs/api/java/lang/Exception.html)>, map:&nbsp;(O)&nbsp;->&nbsp;T): ActionListener<O>` |
| [stringField](string-field.md) | `fun <T&nbsp;:&nbsp;Enum<T>> [XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<T>.~~stringField~~(field:&nbsp;T, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit` |
| [stringFieldMapping](string-field-mapping.md) | `fun <T&nbsp;:&nbsp;Enum<T>> [XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<T>.stringFieldMapping(field:&nbsp;T, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit`
`fun <T&nbsp;:&nbsp;Any> [XContentJsonObjectWithClass](-x-content-json-object-with-class/index.md)<T>.stringFieldMapping(field:&nbsp;KProperty1<T,&nbsp;*>, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit`
`fun [XContentJsonObject](-x-content-json-object/index.md).stringFieldMapping(field:&nbsp;String, indexed:&nbsp;[EsIndexedField](-es-indexed-field/index.md)&nbsp;=&nbsp;EsIndexedField.NOT_ANALYZED, stored:&nbsp;[EsStoredField](-es-stored-field/index.md)&nbsp;=&nbsp;EsStoredField.NOT_STORED, init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit&nbsp;=&nbsp;{}): Unit` |
| [wrapThrowable](wrap-throwable.md) | `fun wrapThrowable(rawEx:&nbsp;Throwable): [Exception](http://docs.oracle.com/javase/6/docs/api/java/lang/Exception.html)` |
| [xsonArray](xson-array.md) | `fun xsonArray(init:&nbsp;[XContentJsonArray](-x-content-json-array/index.md).()&nbsp;->&nbsp;Unit): XContentBuilder` |
| [xsonObject](xson-object.md) | `fun xsonObject(init:&nbsp;[XContentJsonObject](-x-content-json-object/index.md).()&nbsp;->&nbsp;Unit): XContentBuilder` |
| [xsonObjectWithFieldClass](xson-object-with-field-class.md) | `fun <T&nbsp;:&nbsp;Any> xsonObjectWithFieldClass(init:&nbsp;[XContentJsonObjectWithClass](-x-content-json-object-with-class/index.md)<T>.()&nbsp;->&nbsp;Unit): XContentBuilder` |
| [xsonObjectWithFieldEnum](xson-object-with-field-enum.md) | `fun <T&nbsp;:&nbsp;Enum<T>> xsonObjectWithFieldEnum(init:&nbsp;[XContentJsonObjectWithEnum](-x-content-json-object-with-enum/index.md)<T>.()&nbsp;->&nbsp;Unit): XContentBuilder` |