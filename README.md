# MyFrappeDocumentation
Documentation that i made myself while studying Frappe Framework

1. Create and Configure new Doctype
   - Simply search for 'New DocType'
    
     ![Search'NewDocType'](https://github.com/MRaynardAlif/MyFrappeDocumentation/assets/86415726/f6efbeb7-4e2a-4b2f-8190-00b77c6809a0)

   - Configure the DocType as whatever you need
    
     ![Configure](https://github.com/MRaynardAlif/MyFrappeDocumentation/assets/86415726/0f54ea48-2981-4f18-afba-a47f27bc6b33)

   - Configure the Field
    
     ![ConfigureField](https://github.com/MRaynardAlif/MyFrappeDocumentation/assets/86415726/2bebda34-38fe-437e-a69e-f376aaf34abc)

     You can set the field whatever you want

  2. Set DocType Connection
     
     Form here, we will focus to the connection between DocType.
     - For Tree (Parent and Child) Connection

       Create the Parent and Child DocType

       For Parent DocType, simply configure it like this :
       ![image](https://github.com/MRaynardAlif/MyFrappeDocumentation/assets/86415726/c7a2befc-f4c1-4662-9663-47c26600c785)

       After that, add the field you need.
       
       When you save it, it will automaticly generate these field
       ![image](https://github.com/MRaynardAlif/MyFrappeDocumentation/assets/86415726/7e63be8a-b94d-465d-9638-8885f812c6ef)

       For Child DocType, configure in like this :
       
       ![image](https://github.com/MRaynardAlif/MyFrappeDocumentation/assets/86415726/9c2c8e4b-9009-4ccd-b2c1-cfe256304541)

       Add field option with the Parent DocType Label
       
       ![image](https://github.com/MRaynardAlif/MyFrappeDocumentation/assets/86415726/a0c087fd-0f5d-459b-99cf-fce38cae5b3a)

       To connect the Child DocType Fields to the Parent DocType, simply Add the Child DocType Mandatory Field to the Parent DocType Field, then set the field type        as table and set the option with Child DocType Label like this :

       ![image](https://github.com/MRaynardAlif/MyFrappeDocumentation/assets/86415726/de0c6f91-4d46-4085-ae14-d17796fefa79)

     - For DocType Link Connection

       Simply create two new DocType with whatever configuration you want. For example, i already created two DocType with the Label 'Employees' and 'Work Order',         and i want to make each Employees can create their own Work Order with their name in it so they know which Work Order that they are created because it              connected to their Doctype.

       First, Create a mandatory field in Work Order Doctype, set the type as 'Link' and set the option with the DocType Label you want to connect with, in this           case :
    
       ![image](https://github.com/MRaynardAlif/MyFrappeDocumentation/assets/86415726/37ff5559-328c-4bcf-8825-59979a780365)

       This field is alredy linked to the Employees DocType
     
       Customize the Employees DocType and Add the Document Links, add the DocType Label and the Link Type Field Name, in this case it will be like this :

       ![image](https://github.com/MRaynardAlif/MyFrappeDocumentation/assets/86415726/cd618e89-aa54-44d5-94f7-e1dc4c7e7260)

       you can create as many connections to any DocType as you need, as long as it has Link Type Field inside. 

       Then, you will see the DocType Connections like this :

       ![image](https://github.com/MRaynardAlif/MyFrappeDocumentation/assets/86415726/8f7ab9c3-ee32-4c46-b381-12414f6d35c4)

       Click the 'Work Order' Connections, and it will Automatically open the Work Order DocType List with filtered page to show the specific Work Order that              created by specific Employee, like this:

       ![image](https://github.com/MRaynardAlif/MyFrappeDocumentation/assets/86415726/89163c1e-1fa1-4dab-a836-4ee26661b8e1)

       This Employee hasn't created any Work Order, so let's create one for example:

       ![image](https://github.com/MRaynardAlif/MyFrappeDocumentation/assets/86415726/82b02581-aed9-4230-b152-53c0f9ec1771)

       As you can see, the field 'Request By' is Automatically generate the Employee's name, let's edit it in the full form, then save it.
       
       ![image](https://github.com/MRaynardAlif/MyFrappeDocumentation/assets/86415726/d8d41009-56cb-4ce6-93d1-58449cf18dfa)

       After you save it, back to the Employee and check if it's already connected with the Work Order, if it connected, it will become like this :

       ![image](https://github.com/MRaynardAlif/MyFrappeDocumentation/assets/86415726/b6432a98-9a31-40d7-a9c5-38c84647fbcc)

       This mean this Employee already connected to one created Work Order, and when you clicked it will show the list of created Work Order :
    
       ![image](https://github.com/MRaynardAlif/MyFrappeDocumentation/assets/86415726/c51b0fdd-e825-4828-9b5b-6e8ff1b4a918)
 
     
       ![image](https://github.com/MRaynardAlif/MyFrappeDocumentation/assets/86415726/99ba80e9-a10b-4ca9-8318-3a95453891b3)

       
