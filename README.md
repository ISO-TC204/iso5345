# Registry of Intelligent Transport System Items (RITSI) - DRAFT
This site publishes identifier assignments for registered items that are recognized by International Organization for Standardization (ISO) Technical Committee (TC) 204, _Intelligent transport systems_ (ITS). 

## Background

Within information exchanges, there is often a need to unambiguously and concisely represent information. One way to achieve this is to define an identifier (e.g., an integer value) that can be used to concisely represent a specific meaning (e.g., the reference to a country, a standard, a protocol). The identifier might be an integer, a hierarchical structure (e.g., an ASN.1 OBJECT IDENTIFIER), a textual name, or any other concise representation (e.g., a two-character country code). 

The mappings of identifeirs to their precise meanings is provided by a list of **registered items**. A list of registered items is presented as a table with columns representing different attributes of each registered item and each row associating a specific registered item with its assigned identifier and other attributes (e.g. date of registration). 

Separate lists of registered items allow the same code (e.g., an integer value of '1') to be assigned different meanings in different contexts; these separate lists are known as **item classes**. ISO/TC 204 has identified the need for multiple item classes. Whenever a standard provides a field that can be used to reference a registered item, it must identify the item class (i.e., the specific list of registered items) to be used when populating the field.

Some lists of registered items are relatively static and are only updated when the text of the standard is updated. However, within ITS, several of these lists need to be updated in a more timely manner. ISO/TC 204 developed ISO 5345 to define the process for maintaining such lists. This website provides the official lists of registered items that are maintained per ISO 5345.

## List maintenance

This site is maintained according to the procedures defined in ISO 5345, _Intelligent transport systems – Identifiers_ and the internal ISO/TC 204 Terms of Reference for this document. These documents specify that a maintenance agency reviews submittals and submits its recommendations to ISO/TC 204. If any objections are made to the recommended action, the full membership of ISO/TC 204 discusses the request at their next plenary and makes a final decision. 

The current maintenance agency is listed on the [ISO maintenance agency website](https://www.iso.org/maintenance_agencies.html#5345). Parties who wish to request any change to the list of registered items should submit a completed request [form](form.html) to the maintenance agency.

## Item classes

### General
This website includes a number of distinct registered item listings; each listing is known as an item class. The following clauses provide the formal definition for each item class and a link to a page that lists the registered items for that item class. 

The definition of each item class includes the identification of the attribuites that are associated with each item class. The attributes referenced within these definitions are defined in ISO 5345. Each attribute is marked as mandatory (M), conditional (C), or optional (O). Requests for registering new items within a list must specify the item class and all of the applicable attributes that are marked with an asterisk; the attributes not marked with an asterisk are provided by the maintenance agency. **It is the responsibility of requesters to review the existing registered items to ensure that they are not duplicating assignments.**

The following attributes are associated with registered items for all item classes.

- ID (M)
- Name (*M)
- Description (*M)
- Assignee (*M)
- Updated (M)
- State (M)

The following sections define each item class supported by the RITSI with a textual description of the item class and a table with the following columns (per the rules of ISO 5345).  

- Special attributes: Lists any attributes (in addition to those identified above) that are to be associated with each registered item within the item class
- Policy: Identifies the ISO 5345-defined policy used to make assignments within the item class
- Datatype: Identifies the type of identifier assigned to registered items within the item class
- Standards: Identifies standards that are known to rely upon the listing of registered items within the item class

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

## Policies

<a name="general"></a>
###	General
The general policy allows anyone to submit a request related to the item list.

<a name="national"></a>
###	National body policy
The national body policy requires all requests related to the item list to be submitted by a P-member of ISO/TC 204.



