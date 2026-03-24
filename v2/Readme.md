# *MISION 1*

Lo que hice es crear el grupo con:

<xs:attributeGroup name="AtributosServidor">
        <xs:attribute name="id" type="TipoIdServidor" use="required"/>
        <xs:attribute name="rack" type="TipoRack" use="required"/>
        <xs:attribute name="estado" type="TipoEstado" use="required"/>
    </xs:attributeGroup>

Y luego lo llame con:

 <xs:attributeGroup ref="AtributosServidor"/>

*MISION 2*

 Con esta mision hice que muchas lineas sean cortadas
 Cree el grupo que me dijeron y luego lo use en Hardware

*MISION 3*
Puse minOcurrs y maxOcurrs

*MISION 4*
Cree el nuevo elemento llamado red, luego en el xml puse una ip fija

*MISION 5*
Añadi la etiqueta auditoria para usar el xs:all

<xs:element name="auditoria">
<xs:complexType>
<xs:all>
<xs:element name="fecha_revision" type="xs:date"/>
<xs:element name="tecnico" type="xs:string"/>
<xs:element name="nota" type="xs:string"/>
</xs:all>

*MISION 6*
Añadi abajo del xsd para que sea unique
 
HE AHORRADO UNA 30 LINEAS MAS O MENOS
EL ERROR QUE ME DA ES DUPLICATE VALUE (UNIQUE)



 
