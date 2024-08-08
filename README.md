# Registry of Intelligent Transport System Items (RITSI)
This site publishes identifier assignments for registered items that are recognized by the International Organization for Standardization (ISO) Technical Committee (TC) 204, _Intelligent transport systems_ (ITS). For more information about this site, see our [background](background.md) page.

## Request a New Identifier
To request a new identifier, please use the following forms:

- [Form](ITS-AID_Request_Form.pdf) to request a new ITS-AID assignment
- [Form](ITS_Identifier_Request_Form.pdf) to request a new assignment for any other identifier

## Identifiers

### [ITS-AID](its-aid.md)

An ITS application identifier (ITS-AID) provides a globally unique identifier for an ITS application specification. Registered items are defined per the rules contained in the following table. The list of ITS-AID registered items is provided [here](its-aid.md). 

<table style="width: 1000px">
	<caption>ITS-AID Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
  	<td>
  		<table>
  			<tr><td>Service type (*O)</td></tr>
  			<tr><td>p-encoding (M)</td></tr>
			<tr><td>Specification (*M, <abbr title="Public access is required for identifier values less than 16,512">Pub/Priv</abbr>)</td></tr>
  			<tr><td>Uses (*M)</td></tr>
			<tr><td>URL (*C, <abbr title="Required for public specifications">Pub</abbr>)</td></tr>
  		</table>
  	</td>
  	<td><a href="#general">General Policy</a></td>
  	<td>INTEGER</td>
  	<td>
  		<table>
  		<tr><td>ETSI 103 097</td></tr>
  		<tr><td>ETSI 302 636-5-1</td></tr>
  		<tr><td>IEEE 1609.2</td></tr>
  		<tr><td>IEEE 1609.3</td></tr>
  		<tr><td>ISO 16460</td></tr>
  		<tr><td>EN ISO 17423 </td></tr>
  		<tr><td>CEN ISO 17429</td></tr>
  		<tr><td>ISO 21218</td></tr>
  		<tr><td>ISO 22418</td></tr>
  		<tr><td>ISO 24102-1</td></tr>
  		<tr><td>ISO 24102-2</td></tr>
  		<tr><td>ISO 29281-1</td></tr>
  		</table>
  	</td>
  </tr>
</table>

### [ITS-ATT](its-att.md)

An ITS access technology type (ITS-ATT) provides a globally unique identifier for an ITS access technology; this identifier was formerly called the medium type (MedType). Registered items are defined per the rules contained in the following table. The list of ITS-ATT registered items is provided [here](its-att.md). 
 

<table style="width: 1000px">
	<caption>ITS-ATT Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td>
		<table>
			<tr><td>Specification (*M, <abbr title="Public access is required">Pub</abbr>)</td></tr>
			<tr><td>URL (*M)</td></tr>
		</table>
	</td>
    <td><a href="#general">General Policy</a></td>
    <td>INTEGER (0..255)</td>
    <td>
		<table>
		<tr><td>ISO 16460</td></tr>
		<tr><td>ISO 21218</td></tr>
		<tr><td>ISO 22418</td></tr>
		<tr><td>ISO 24102-1</td></tr>
		<tr><td>ISO 24102-3</td></tr>
		<tr><td>ISO 24102-4</td></tr>
		<tr><td>ISO 24102-6</td></tr>
		</table>
	</td>
  </tr>
</table>

### [ITS-FlowTypeID](its-flowtypeid.md)

An ITS flow type identifier (ITS-FlowTypeID) provides a globally unique identifier for an ITS flow type, which is a set of communication requirements and objectives as specified in EN ISO 17423. Registered items are defined per the rules contained in the following table. The list of registered items is provided [here](its-flowtypeid.md). 
 

<table style="width: 1000px">
	<caption>ITS-FlowTypeID Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td>
		<table>
			<tr><td>Specification (*M, <abbr title="Public access is required">Pub</abbr>)</td></tr>
			<tr><td>URL (*M)</td></tr>
		</table>
	</td>
    <td><a href="#general">General Policy</a></td>
    <td>INTEGER (0..65535)</td>
    <td>
		<table>
		<tr><td>EN ISO 17423</td></tr>
		<tr><td>ISO 24102-6</td></tr>
		</table>
	</td>
  </tr>
</table>

### [ITS-LCHID](its-lchid.md)

An ITS logical channel identifier (ITS-LCHID) provides a globally unique identifier for an ITS logical channel. Registered items are defined per the rules contained in the following table. The list of registered items is provided [here](its-lchid.md). 
 

<table style="width: 1000px">
	<caption>ITS-LCHID Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td>
		<table>
			<tr><td>Acronym (*M)</td></tr>
			<tr><td>Specification (*M, <abbr title="Public access is required">Pub</abbr>)</td></tr>
			<tr><td>URL (*M)</td></tr>
		</table>
	</td>
    <td><a href="#national">National Body Policy</a></td>
    <td>INTEGER (0..65535)</td>
    <td>
		<table>
		<tr><td>EN ISO 17423</td></tr>
		<tr><td>ISO 21218</td></tr>
		<tr><td>ISO 24102-6</td></tr>
		</table>
	</td>
  </tr>
</table>

### [ITS-MsgSetID](its-msgsetid.md)

An ITS message set identifier (ITS-MsgSetID) provides a globally unique identifier for an ITS message set. Registered items are defined per the rules contained in the following table. The list of registered items is provided [here](its-msgsetid.md). 
 

<table style="width: 1000px">
	<caption>ITS-MsgSetID Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td>
		<table>
			<tr><td>p-encoding (M)</td></tr>
			<tr><td>Specification (*C, <abbr title="Public access is required for identifier values less than 16,512">Pub</abbr>)</td></tr>
			<tr><td>URL (*M)</td></tr>
		</table>
	</td>
    <td>Identifier values < 16512: <a href="#national">National Body Policy</a><br />
    Identifier values >= 16512: <a href="#general">General Policy</a></td>
    <td>INTEGER</td>
    <td>
		<table>
		<tr><td>CEN ISO 17429</td></tr>
		</table>
	</td>
  </tr>
</table>

### [ITS-OrgID](its-orgid.md)

An ITS organization identifier (ITS-OrgID) provides a globally unique identifier for an organization that needs to be identified within ITS communications. Registered items are defined per the rules contained in the following table. The list of registered items is provided [here](its-orgid.md). 
 

<table style="width: 1000px">
	<caption>ITS-OrgID Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td>
		<table>
			<tr><td>Address (*M, not published)</td></tr>
			<tr><td>E-mail (*M, not published)</td></tr>
			<tr><td>URL (*M)</td></tr>
		</table>
	</td>
    <td><a href="#general">General Policy</a></td>
    <td>OBJECT IDENTIFIER</td>
    <td>
		<table>
		<tr><td>ISO 24102-2</td></tr>
		</table>
	</td>
  </tr>
</table>

### [ITS-PN-FNTP](its-pn-fntp.md)

An ITS port number for the fast networking and transport layer protocol (ITS-PN-FNTP) provides a globally unique identifier for a higher-layer ITS protocol that uses the FNTP protocol defined by ISO 29281-1. Registered items are defined per the rules contained in the following table. The list of registered items is provided [here](its-pn-fntp.md). 
 

<table style="width: 1000px">
	<caption>ITS-PN-FNTP Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td>
		<table>
			<tr><td>Specification (*M, <abbr title="Public access is required">Pub</abbr>)</td></tr>
			<tr><td>URL (*M)</td></tr>
		</table>
	</td>
    <td><a href="#general">General Policy</a></td>
    <td>INTEGER (0..65535)</td>
    <td>
		<table>
		<tr><td>ISO 29281-1</td></tr>
		<tr><td>ISO 29281-2</td></tr>
		</table>
	</td>
  </tr>
</table>

### [ITS-PRID](its-prid.md)

An ITS policy region iidentifier (ITS-PRID) provides a globally unique identifier for an ITS policy region. Registered items are defined per the rules contained in the following table. The list of registered items is provided [here](its-prid.md). 
 

<table style="width: 1000px">
	<caption>ITS-PRID Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td>
		<table>
			<tr><td>Boundaries (*M)</td></tr>
		</table>
	</td>
    <td><a href="#national">National Body Policy</a></td>
    <td>OBJECT IDENTIFIER</td>
    <td>
		<table>
		</table>
	</td>
  </tr>
</table>

### [ITS-ProtID](its-protid.md)

An ITS access technology type (ITS-ATT) provides a globally unique identifier for a non-parameterized ITS (communications) protocol that may reside in an ITS-SU. Registered items are defined per the rules contained in the following table. The list of registered items is provided [here](its-protid.md). 
 

<table style="width: 1000px">
	<caption>ITS-ProtID Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td>
		<table>
			<tr><td>Specification (*M, <abbr title="Public access is required">Pub</abbr>)</td></tr>
			<tr><td>URL (*M)</td></tr>
		</table>
	</td>
    <td><a href="#general">General Policy</a></td>
    <td>OBJECT IDENTIFIER</td>
    <td>
		<table>
		<tr><td>ISO 16460</td></tr>
		<tr><td>ISO 17423</td></tr>
		<tr><td>ISO 22418</td></tr>
		<tr><td>ISO 24102-2</td></tr>
		</table>
	</td>
  </tr>
</table>

### [ITS-ProtStckID](its-protstckid.md)

An ITS access technology type (ITS-ATT) provides a globally unique identifier for a non-parameterized communications protocol stack; this identifier is known as the ITS-S-CPID in ISO 24102-6. Registered items are defined per the rules contained in the following table. The list of registered items is provided [here](its-protstckid.md). 
 

<table style="width: 1000px">
	<caption>ITS-ProtStckID Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td>
		<table>
			<tr><td>Protocols (*M)</td></tr>
		</table>
	</td>
    <td><a href="#general">General Policy</a></td>
    <td>INTEGER</td>
    <td>
		<table>
		<tr><td>ISO 17423</td></tr>
		<tr><td>ISO 24102-6</td></tr>
		</table>
	</td>
  </tr>
</table>

### [ITS-RRID](its-rrid.md)

An ITS regulatory region identifier (ITS-RRID) provides a globally unique identifier for an ITS regulatory region, such as regions for:

- radio regulation
- security regulation
- privacy regulation
- traffic regulation

Registered items are defined per the rules contained in the following table. The list of registered items is provided [here](its-rrid.md). 
 

<table style="width: 1000px">
	<caption>ITS-RRID Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td>
		<table>
			<tr><td>Boundaries (*M)</td></tr>
		</table>
	</td>
    <td><a href="#national">National Body Policy</a></td>
    <td>OBJECT IDENTIFER</td>
    <td>
		<table>
		</table>
	</td>
  </tr>
</table>

### [ITS-S-APDID](its-s-apdid.md)

An ITS station application process developer identifier (ITS-S-APDID) provides a globally unique identifier for the developer of an ITS station application process. Registered items are defined per the rules contained in the following table. The list of registered items is provided [here](its-s-apdid.md). 
 

<table style="width: 1000px">
	<caption>ITS-S-APDID Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td>
		<table>
		</table>
	</td>
    <td><a href="#general">General Policy</a></td>
    <td>OBJECT IDENTIFIER</td>
    <td>
		<table>
		<tr><td>ISO 24102-2</td></tr>
		</table>
	</td>
  </tr>
</table>

### [ITS-S-APPID](its-s-appid.md)

An ITS station application process provisioner identifier (ITS-S-APPID) provides a globally unique identifier for a provisioner for an ITS station application process. Registered items are defined per the rules contained in the following table. The list of registered items is provided [here](its-s-appid.md). 
 

<table style="width: 1000px">
	<caption>ITS-S-APPID Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td>
		<table>
		</table>
	</td>
    <td><a href="#general">General Policy</a></td>
    <td>OBJECT IDENTIFIER</td>
    <td>
		<table>
		<tr><td>ISO 18750</td></tr>
		<tr><td>ISO 22418</td></tr>
		</table>
	</td>
  </tr>
</table>

### [ITS-S-MSEID](its-s-mseid.md)

An ITS station managed service entity identifier (ITS-S-MSEID) provides a globally unique identifier for a uniquely addressable entity in an ITS-S layer comprised of a set of related ITS-S capabilities. Registered items are defined per the rules contained in the following table. The list of registered items is provided [here](its-s-mseid.md). 
 

<table style="width: 1000px">
	<caption>ITS-S-MSEID Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td>
		<table>
			<tr><td>Specification (*M, <abbr title="Public access is required">Pub</abbr>)</td></tr>
			<tr><td>URL (*M)</td></tr>
		</table>
	</td>
    <td><a href="#general">General Policy</a></td>
    <td>OBJECT IDENTIFIER</td>
    <td>
		<table>
				<tr><td>ISO 17429</td></tr>
		</table>
	</td>
  </tr>
</table>

### [ITS-S-MSECID](its-s-msecid.md)

An ITS station managed service entity capability identifier (ITS-S-MSECID) provides a globally unique identifier for a uniquely addressable protocol functionality within an ITS station. Registered items are defined per the rules contained in the following table. The list of registered items is provided [here](its-s-msecid.md). 
 

<table style="width: 1000px">
	<caption>ITS-S-MSECID Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td>
		<table>
			<tr><td>Specification (*M, <abbr title="Public access is required">Pub</abbr>)</td></tr>
			<tr><td>URL (*M)</td></tr>
		</table>
	</td>
    <td><a href="#general">General Policy</a></td>
    <td>OBJECT IDENTIFIER</td>
    <td>
		<table>
		<tr><td>ISO 24102-6</td></tr>
		</table>
	</td>
  </tr>
</table>

### [ITS-SCU-CMCID](its-scu-cmcid.md)

An ITS station communications unit configuration management centre identifier (ITS-SCU-CMCID) provides a globally unique identifier for a configuration management centre that is responsible for the configuration of the ITS-SCU. Registered items are defined per the rules contained in the following table. The list of registered items is provided [here](its-scu-cmcid.md). 
 

<table style="width: 1000px">
	<caption>ITS-SCU-CMCID Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td>
		<table>
		</table>
	</td>
    <td><a href="#general">General Policy</a></td>
    <td>OBJECT IDENIFIER</td>
    <td>
		<table>
		<tr><td>ISO 24102-2</td></tr>
		</table>
	</td>
  </tr>
</table>

### [ITS-SEMID](its-semid.md)

An ITS station equipment manufacturer identifier (ITS-SEMID) provides a globally unique identifier for an equipment manufacturer of ITS stations. Registered items are defined per the rules contained in the following table. The list of registered items is provided [here](its-semid.md). 
 

<table style="width: 1000px">
	<caption>ITS-SEMID Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td>
		<table>
		</table>
	</td>
    <td><a href="#general">General Policy</a></td>
    <td>OBJECT IDENTIFIER</td>
    <td>
		<table>
		<tr><td>ISO 16460</td></tr>
		<tr><td>ISO 17423</td></tr>
		<tr><td>ISO 21218</td></tr>
		<tr><td>ISO 22418</td></tr>
		<tr><td>ISO 24102-1</td></tr>
		<tr><td>ISO 24102-3</td></tr>
		<tr><td>ISO 24102-4</td></tr>
		<tr><td>ISO 24102-6</td></tr>
		<tr><td>ISO 29281-1</td></tr>
		</table>
	</td>
  </tr>
</table>

### [ITS-SRSAType](its-srsa.md)

Supplemental roadside sensor/actuators (SRSA) represent devices that can be connected to a roadside device to provide supplemental input/output (i.e., simple input and output that is not the primary function of the roadside devic). The type of data provided and representational form is defined by the ITS-SRSA type code (ITS-SRSAType). Registered items are defined per the rules contained in the following table. The list of registered items is provided [here](its-srsa.md). 
 

<table style="width: 1000px">
	<caption>ITS-SRSA Definition</caption>
  <tr>
	<th>Special Attributes</th>
	<th>Policy</th>
	<th>Datatype</th>
	<th>Standards</th>
  </tr>
  <tr>
    <td width="40%">
		<table>
			<tr><td>Specification</td></tr>
			<tr><td>Direction</td></tr>
			<tr><td>Recommended Units</td></tr>
			<tr><td>Recommended Exponent</td></tr>
			<tr><td>Maximum Imprecision</td></tr>
			<tr><td>Test Activation</td></tr>
		</table>
	</td>
    <td><a href="#general">General Policy</a></td>
    <td>PrintableString (SIZE(3))</td>
    <td>
		<table>
		<tr><td>ISO 26048-1</td></tr>
		</table>
	</td>
  </tr>
</table>

In addition, codes are allocated according to the following policies:

- Codes defined within ISO standards shall be assiged a code with all upper-case letters 
- Codes defined by other standards shall be assigned a code with all lower-case letters
- Non-standard codes shall be assigned a code with an initial hyphen
- Codes starting with a question mark (?) are reserved for unregistered use (and may have different meanings in different implementations)

Additional allocations or re-allocations may be made as required.

The special attributes have the following details:

- Direction indicates the direction of the port, one of:
 - input, indicates a sensor
 - output, indicates an actuator
 - bi-directional, indicates a combined sensor and actuator
- Recommended Unit indicates the unit of measure to be applied to the value received from the port (e.g., metres)
- Recommended Exponent indicates the factor of 10 applied to the units (e.g., if units is metre and exponent is -2, the value is reported in centimetres)
- Maximum Imprecision indicates the maximum various to be expected across multiple readings of the same value, expressed in the same units as the reported value. For example, if the imprecision is "<100" in the above example, one would expect that multiple readings taken of the same condition could have a variance of up to 1 metre of each other.
- Test Activation indicates whether the sensor requires support for active testing

## Policies

<a name="general"></a>
###	General
The general policy allows anyone to submit a request related to the item list.

<a name="national"></a>
###	National body policy
The national body policy requires all requests related to the item list to be submitted by a P-member of ISO/TC 204.



