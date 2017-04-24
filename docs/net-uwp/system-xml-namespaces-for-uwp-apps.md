---
title: "System.Xml namespaces for UWP apps | Microsoft Docs"
ms.custom: ""
ms.date: "12/14/2016"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 3be72582-0598-4a8c-b9a0-b3fc83ca8c9d
caps.latest.revision: 6
author: "msatranjr"
ms.author: "misatran"
manager: "markl"
---
# System.Xml namespaces for UWP apps
`System.Xml` and its child namespaces (`System.Xml.Linq`, `System.Xml.Schema`, and `System.Xml.Serialization`) contain types for processing XML.  
  
 This topic displays the types in the `System.Xml` namespaces that are included in .NET for UWP apps. Note that .NET for UWP apps does not include all the members of each type. For information about individual types, see the linked topics. The documentation for a type indicates which members are included in .NET for UWP apps.  
  
## System.Xml namespace  
  
|Types supported in .NET for UWP apps|Description|  
|------------------------------------------------------------------------------------------|-----------------|  
|<xref:System.Xml.ConformanceLevel>|Specifies the amount of input or output checking that the created XmlReader and XmlWriter objects perform.|  
|<xref:System.Xml.DtdProcessing>|Specifies the options for processing DTDs. The DtdProcessing enumeration is used by XmlReaderSettings.|  
|<xref:System.Xml.IXmlDictionary>|An interface that defines the contract that an Xml dictionary must implement to be used by XmlDictionaryReader and XmlDictionaryWriter implementations.|  
|<xref:System.Xml.IXmlLineInfo>|Provides an interface to enable a class to return line and position information.|  
|<xref:System.Xml.IXmlNamespaceResolver>|Provides read-only access to a set of prefix and namespace mappings.|  
|<xref:System.Xml.NamespaceHandling>|Specifies whether to remove duplicate namespace declarations in the XmlWriter.|  
|<xref:System.Xml.NameTable>|Implements a single-threaded XmlNameTable.|  
|<xref:System.Xml.NewLineHandling>|Specifies how to handle line breaks.|  
|<xref:System.Xml.OnXmlDictionaryReaderClose>|delegate for a callback method when closing the reader.|  
|<xref:System.Xml.ReadState>|Specifies the state of the reader.|  
|<xref:System.Xml.UniqueId>|A unique identifier optimized for Guids.|  
|<xref:System.Xml.WriteState>|Specifies the state of the XmlWriter.|  
|<xref:System.Xml.XmlAttribute>|Represents an attribute. Valid and default values for the attribute are defined in a document type definition (DTD) or schema.|  
|<xref:System.Xml.XmlAttributeCollection>|Represents a collection of attributes that can be accessed by name or index.|  
|<xref:System.Xml.XmlBinaryReaderSession>|Enables optimized strings to be managed in a dynamic way.|  
|<xref:System.Xml.XmlBinaryWriterSession>|Enables using a dynamic dictionary to compress common strings that appear in a message and maintain state.|  
|<xref:System.Xml.XmlCDataSection>|Represents a CDATA section.|  
|<xref:System.Xml.XmlCharacterData>|Provides text manipulation methods that are used by several classes.|  
|<xref:System.Xml.XmlComment>|Represents the content of an XML comment.|  
|<xref:System.Xml.XmlConvert>|Encodes and decodes XML names and provides methods for converting between common language runtime types and XML Schema definition language (XSD) types. When converting data types the values returned are locale independent.|  
|<xref:System.Xml.XmlDateTimeSerializationMode>|Specifies how to treat the time value when converting between string and DateTime.|  
|<xref:System.Xml.XmlDeclaration>|Represents the XML declaration node \<?xml version='1.0'...?>.|  
|<xref:System.Xml.XmlDictionary>|Implements a dictionary used to optimize Windows Communication Foundation (WCF)’s XML reader/writer implementations.|  
|<xref:System.Xml.XmlDictionaryReader>|An abstract class that the Windows Communication Foundation (WCF) derives from to do serialization and deserialization.|  
|<xref:System.Xml.XmlDictionaryReaderQuotas>|Contains configurable quota values for XmlDictionaryReaders.|  
|<xref:System.Xml.XmlDictionaryReaderQuotaTypes>|Enumerates the configurable quota values for XmlDictionaryReaders.|  
|<xref:System.Xml.XmlDictionaryString>|Represents an entry stored in a XmlDictionary.|  
|<xref:System.Xml.XmlDictionaryWriter>|An abstract class that the Windows Communication Foundation (WCF) derives from to do serialization and deserialization.|  
|<xref:System.Xml.XmlDocument>|Represents an XML document. You can use this class to load; validate; edit; add; and position XML in a document. For examples; see the Remarks section on this page.|  
|<xref:System.Xml.XmlDocumentFragment>|Represents a lightweight object that is useful for tree insert operations.|  
|<xref:System.Xml.XmlElement>|Represents an element.|  
|<xref:System.Xml.XmlException>|Returns detailed information about the last exception.|  
|<xref:System.Xml.XmlImplementation>|Defines the context for a set of XmlDocument objects.|  
|<xref:System.Xml.XmlLinkedNode>|Gets the node immediately preceding or following this node.|  
|<xref:System.Xml.XmlNamedNodeMap>|Represents a collection of nodes that can be accessed by name or index.|  
|<xref:System.Xml.XmlNamespaceManager>|Resolves, adds, and removes namespaces to a collection and provides scope management for these namespaces.|  
|<xref:System.Xml.XmlNamespaceScope>|Defines the namespace scope.|  
|<xref:System.Xml.XmlNameTable>|Table of atomized string objects.|  
|<xref:System.Xml.XmlNode>|Represents a single node in the XML document.|  
|<xref:System.Xml.XmlNodeChangedAction>|Specifies the type of node change.|  
|<xref:System.Xml.XmlNodeChangedEventArgs>|Provides data for the NodeChanged; NodeChanging; NodeInserted; NodeInserting; NodeRemoved and NodeRemoving events.|  
|<xref:System.Xml.XmlNodeChangedEventHandler>|Represents the method that handles NodeChanged; NodeChanging; NodeInserted; NodeInserting; NodeRemoved and NodeRemoving events.|  
|<xref:System.Xml.XmlNodeList>|Represents an ordered collection of nodes.|  
|<xref:System.Xml.XmlNodeOrder>|Describes the document order of a node compared to a second node.|  
|<xref:System.Xml.XmlNodeType>|Specifies the type of node.|  
|<xref:System.Xml.XmlParserContext>|Provides all the context information required by the XmlReader to parse an XML fragment.|  
|<xref:System.Xml.XmlProcessingInstruction>|Represents a processing instruction; which XML defines to keep processor-specific information in the text of the document.|  
|<xref:System.Xml.XmlQualifiedName>|Represents an XML qualified name.|  
|<xref:System.Xml.XmlReader>|Represents a reader that provides fast, non-cached, forward-only access to XML data.|  
|<xref:System.Xml.XmlReaderSettings>|Specifies a set of features to support on the XmlReader object created by the Create method.|  
|<xref:System.Xml.XmlSignificantWhitespace>|Represents white space between markup in a mixed content node or white space within an xml:space= 'preserve' scope. This is also referred to as significant white space.|  
|<xref:System.Xml.XmlSpace>|Specifies the current xml:space scope.|  
|<xref:System.Xml.XmlText>|Represents the text content of an element or attribute.|  
|<xref:System.Xml.XmlWhitespace>|Represents white space in element content.|  
|<xref:System.Xml.XmlWriter>|Represents a writer that provides a fast, non-cached, forward-only means of generating streams or files containing XML data.|  
|<xref:System.Xml.XmlWriterSettings>|Specifies a set of features to support on the XmlWriter object created by the Create method.|  
  
## System.Xml.Linq namespace  
  
|Types supported in the .NET for UWP apps|Description|  
|----------------------------------------------------------------------------------------------|-----------------|  
|<xref:System.Xml.Linq.Extensions>|Contains the LINQ to XML extension methods.|  
|<xref:System.Xml.Linq.LoadOptions>|Specifies load options when parsing XML.|  
|<xref:System.Xml.Linq.ReaderOptions>|Specifies whether to omit duplicate namespaces when loading an XDocument with an XmlReader.|  
|<xref:System.Xml.Linq.SaveOptions>|Specifies serialization options.|  
|<xref:System.Xml.Linq.XAttribute>|Represents an XML attribute.|  
|<xref:System.Xml.Linq.XCData>|Represents a text node that contains CDATA.|  
|<xref:System.Xml.Linq.XComment>|Represents an XML comment.|  
|<xref:System.Xml.Linq.XContainer>|Represents a node that can contain other nodes.|  
|<xref:System.Xml.Linq.XDeclaration>|Represents an XML declaration.|  
|<xref:System.Xml.Linq.XDocument>|Represents an XML document.|  
|<xref:System.Xml.Linq.XDocumentType>|Represents an XML Document Type Definition (DTD).|  
|<xref:System.Xml.Linq.XElement>|Represents an XML element.|  
|<xref:System.Xml.Linq.XName>|Represents a name of an XML element or attribute.|  
|<xref:System.Xml.Linq.XNamespace>|Represents an XML namespace. This class cannot be inherited.|  
|<xref:System.Xml.Linq.XNode>|Represents the abstract concept of a node (element, comment, document type, processing instruction, or text node) in the XML tree.|  
|<xref:System.Xml.Linq.XNodeDocumentOrderComparer>|Contains functionality to compare nodes for their document order. This class cannot be inherited.|  
|<xref:System.Xml.Linq.XNodeEqualityComparer>|Compares nodes to determine whether they are equal. This class cannot be inherited.|  
|<xref:System.Xml.Linq.XObject>|Represents a node or an attribute in an XML tree.|  
|<xref:System.Xml.Linq.XObjectChange>|Specifies the event type when an event is raised for an XObject.|  
|<xref:System.Xml.Linq.XObjectChangeEventArgs>|Provides data for the Changing and Changed events.|  
|<xref:System.Xml.Linq.XProcessingInstruction>|Represents an XML processing instruction.|  
|<xref:System.Xml.Linq.XStreamingElement>|Represents elements in an XML tree that supports deferred streaming output.|  
|<xref:System.Xml.Linq.XText>|Represents a text node.|  
|<xref:System.Xml.XPath.Extensions>|Contains the LINQ to XML extension methods.|  
  
## System.Xml.Schema namespace  
  
|Types supported in the .NET for UWP apps|Description|  
|----------------------------------------------------------------------------------------------|-----------------|  
|<xref:System.Xml.Schema.XmlSchema>|An in-memory representation of an XML Schema as specified in the World Wide Web Consortium (W3C) XML Schema Part 1: Structures and XML Schema Part 2: Datatypes specifications.|  
|<xref:System.Xml.Schema.XmlSchemaForm>|Indicates if attributes or elements need to be qualified with a namespace prefix.|  
|<xref:System.Xml.XPath.Extensions>|This class contains the LINQ to XML extension methods for XSD validation.|  
  
## System.Xml.Serialization namespace  
  
|Types supported in the .NET for UWP apps|Description|  
|----------------------------------------------------------------------------------------------|-----------------|  
|<xref:System.Xml.Serialization.IXmlSerializable>|Provides custom formatting for XML serialization and deserialization.|  
|<xref:System.Xml.Serialization.XmlAnyAttributeAttribute>|Specifies that the member (a field that returns an array of XmlAttribute objects) can contain any XML attributes.|  
|<xref:System.Xml.Serialization.XmlAnyElementAttribute>|Specifies that the member (a field that returns an array of XmlElement or XmlNode objects) contains objects that represent any XML element that has no corresponding member in the object being serialized or deserialized.|  
|<xref:System.Xml.Serialization.XmlAnyElementAttributes>|Represents a collection of XmlAnyElementAttribute objects.|  
|<xref:System.Xml.Serialization.XmlArrayAttribute>|Specifies that the XmlSerializer must serialize a particular class member as an array of XML elements.|  
|<xref:System.Xml.Serialization.XmlArrayItemAttribute>|Specifies the derived types that the XmlSerializer can place in a serialized array.|  
|<xref:System.Xml.Serialization.XmlArrayItemAttributes>|Represents a collection of XmlArrayItemAttribute objects.|  
|<xref:System.Xml.Serialization.XmlAttributeAttribute>|Specifies that the XmlSerializer must serialize the class member as an XML attribute.|  
|<xref:System.Xml.Serialization.XmlAttributeOverrides>|Allows you to override property, field, and class attributes when you use the XmlSerializer to serialize or deserialize an object.|  
|<xref:System.Xml.Serialization.XmlAttributes>|Represents a collection of attribute objects that control how the XmlSerializer serializes and deserializes an object.|  
|<xref:System.Xml.Serialization.XmlChoiceIdentifierAttribute>|Specifies that the member can be further detected by using an enumeration.|  
|<xref:System.Xml.Serialization.XmlElementAttribute>|Indicates that a public field or property represents an XML element when the XmlSerializer serializes or deserializes the object that contains it.|  
|<xref:System.Xml.Serialization.XmlElementAttributes>|Represents a collection of XmlElementAttribute objects used by the XmlSerializer to override the default way it serializes a class.|  
|<xref:System.Xml.Serialization.XmlEnumAttribute>|Controls how the XmlSerializer serializes an enumeration member.|  
|<xref:System.Xml.Serialization.XmlIgnoreAttribute>|Instructs the Serialize method of the XmlSerializer not to serialize the public field or public read/write property value.|  
|<xref:System.Xml.Serialization.XmlIncludeAttribute>|Allows the XmlSerializer to recognize a type when it serializes or deserializes an object.|  
|<xref:System.Xml.Serialization.XmlNamespaceDeclarationsAttribute>|Specifies that the target property, parameter, return value, or class member contains prefixes associated with namespaces that are used within an XML document.|  
|<xref:System.Xml.Serialization.XmlRootAttribute>|Controls XML serialization of the attribute target as an XML root element.|  
|<xref:System.Xml.Serialization.XmlSchemaProviderAttribute>|When applied to a type, stores the name of a static method of the type that returns an XML schema and a XmlQualifiedName (or XmlSchemaType for anonymous types) that controls the serialization of the type.|  
|<xref:System.Xml.Serialization.XmlSerializer>|Serializes and deserializes objects into and from XML documents. The XmlSerializer enables you to control how objects are encoded into XML.|  
|<xref:System.Xml.Serialization.XmlSerializerNamespaces>|Contains the XML namespaces and prefixes that the XmlSerializer uses to generate qualified names in an XML-document instance.|  
|<xref:System.Xml.Serialization.XmlTextAttribute>|Indicates to the XmlSerializer that the member must be treated as XML text when the class that contains it is serialized or deserialized.|  
|<xref:System.Xml.Serialization.XmlTypeAttribute>|Controls the XML schema that is generated when the attribute target is serialized by the XmlSerializer.|  
  
## System.Xml.XPath namespace  
  
|Types supported in the .NET for UWP apps|Description|  
|----------------------------------------------------------------------------------------------|-----------------|  
|<xref:System.Xml.XmlDocumentXPathExtensions>|For more information, see <xref:System.Xml.XmlDocumentXPathExtensions>.|  
|<xref:System.Xml.XPath.XDocumentExtensions>|For more information, see <xref:System.Xml.XPath.XDocumentExtensions>.|  
  
## See Also  
 [.NET for Windows apps](../net-uwp/dotnet-for-windows-apps.md)