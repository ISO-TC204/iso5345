# RITSI Background

Within information exchanges, there is often a need to unambiguously and concisely represent information. One way to achieve this is to define an identifier (e.g., an integer value) that can be used to concisely represent a specific meaning (e.g., the reference to a country, a standard, a protocol). The identifier might be an integer, a hierarchical structure (e.g., an ASN.1 OBJECT IDENTIFIER), a textual name, or any other concise representation (e.g., a two-character country code). 

The mappings of identifeirs to their precise meanings is provided by a list of **registered items**. A list of registered items is presented as a table with columns representing different attributes of each registered item and each row associating a specific registered item with its assigned identifier and other attributes (e.g. date of registration). 

Separate lists of registered items allow the same code (e.g., an integer value of '1') to be assigned different meanings in different contexts; these separate lists are known as **item classes**. ISO/TC 204 has identified the need for multiple item classes. Whenever a standard provides a field that can be used to reference a registered item, it must identify the item class (i.e., the specific list of registered items) to be used when populating the field.

Some lists of registered items are relatively static and are only updated when the text of the standard is updated. However, within ITS, several of these lists need to be updated in a more timely manner. ISO/TC 204 developed ISO 5345 to define the process for maintaining such lists. This website provides the official lists of registered items that are maintained per ISO 5345.

### List maintenance

This site is maintained according to the procedures defined in ISO 5345, _Intelligent transport systems – Identifiers_ and the internal ISO/TC 204 Terms of Reference for this document. These documents specify that a maintenance agency reviews submittals and submits its recommendations to ISO/TC 204. If any objections are made to the recommended action, the full membership of ISO/TC 204 discusses the request at their next plenary and makes a final decision. 

The current maintenance agency is listed on the [ISO maintenance agency website](https://www.iso.org/maintenance_agencies.html#5345). Parties who wish to request any change to the list of registered items should submit a completed request [form](form.pdf) to the maintenance agency.

### Item classes

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

