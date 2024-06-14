<mxfile host="app.diagrams.net">
  <diagram name="Diagrama ER">
    <mxGraphModel dx="1208" dy="707" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="2" value="Cliente" style="shape=swimlane;childLayout=stackLayout;horizontal=1;startSize=20;horizontalStack=0;fillColor=#ffffff;swimlaneFillColor=#ffffff;gradientColor=none;swimlaneLine=0;container=1;collapsible=0;" vertex="1" connectable="0" parent="1">
          <mxGeometry x="180" y="60" width="140" height="180" as="geometry" />
        </mxCell>
        <mxCell id="3" value="ID_Cliente" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="2">
          <mxGeometry x="10" y="30" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="4" value="Nombre" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="2">
          <mxGeometry x="10" y="60" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="5" value="Dirección" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="2">
          <mxGeometry x="10" y="90" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="6" value="Teléfono" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="2">
          <mxGeometry x="10" y="120" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="7" value="Email" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="2">
          <mxGeometry x="10" y="150" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="8" value="Asegurado" style="shape=swimlane;childLayout=stackLayout;horizontal=1;startSize=20;horizontalStack=0;fillColor=#ffffff;swimlaneFillColor=#ffffff;gradientColor=none;swimlaneLine=0;container=1;collapsible=0;" vertex="1" connectable="0" parent="1">
          <mxGeometry x="20" y="300" width="140" height="180" as="geometry" />
        </mxCell>
        <mxCell id="9" value="ID_Asegurado" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="8">
          <mxGeometry x="10" y="30" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="10" value="Nombre" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="8">
          <mxGeometry x="10" y="60" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="11" value="Fecha_Nac." style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="8">
          <mxGeometry x="10" y="90" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="12" value="Relación" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="8">
          <mxGeometry x="10" y="120" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="13" value="Póliza" style="shape=swimlane;childLayout=stackLayout;horizontal=1;startSize=20;horizontalStack=0;fillColor=#ffffff;swimlaneFillColor=#ffffff;gradientColor=none;swimlaneLine=0;container=1;collapsible=0;" vertex="1" connectable="0" parent="1">
          <mxGeometry x="350" y="60" width="140" height="180" as="geometry" />
        </mxCell>
        <mxCell id="14" value="ID_Póliza" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="13">
          <mxGeometry x="10" y="30" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="15" value="Tipo" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="13">
          <mxGeometry x="10" y="60" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="16" value="Fecha_Inicio" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="13">
          <mxGeometry x="10" y="90" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="17" value="Fecha_Fin" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="13">
          <mxGeometry x="10" y="120" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="18" value="Cobertura" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="13">
          <mxGeometry x="10" y="150" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="19" value="UsoSeguro" style="shape=swimlane;childLayout=stackLayout;horizontal=1;startSize=20;horizontalStack=0;fillColor=#ffffff;swimlaneFillColor=#ffffff;gradientColor=none;swimlaneLine=0;container=1;collapsible=0;" vertex="1" connectable="0" parent="1">
          <mxGeometry x="20" y="520" width="140" height="300" as="geometry" />
        </mxCell>
        <mxCell id="20" value="ID_Uso" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="19">
          <mxGeometry x="10" y="30" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="21" value="Fecha" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="19">
          <mxGeometry x="10" y="60" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="22" value="Descripción" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="19">
          <mxGeometry x="10" y="90" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="23" value="Procedimiento" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="19">
          <mxGeometry x="10" y="120" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="24" value="Hospitalización" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="19">
          <mxGeometry x="10" y="150" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="25" value="Intervenciones" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="19">
          <mxGeometry x="10" y="180" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="26" value="Médico_Tratante" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="19">
          <mxGeometry x="10" y="210" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="27" value="ID_Asegurado" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="19">
          <mxGeometry x="10" y="240" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="28" value="ID_Póliza" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="19">
          <mxGeometry x="10" y="270" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="29" value="ID_Hospital" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="19">
          <mxGeometry x="10" y="300" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="30" value="Médico" style="shape=swimlane;childLayout=stackLayout;horizontal=1;startSize=20;horizontalStack=0;fillColor=#ffffff;swimlaneFillColor=#ffffff;gradientColor=none;swimlaneLine=0;container=1;collapsible=0;" vertex="1" connectable="0" parent="1">
          <mxGeometry x="350" y="300" width="140" height="180" as="geometry" />
        </mxCell>
        <mxCell id="31" value="ID_Médico" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="30">
          <mxGeometry x="10" y="30" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="32" value="Nombre" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="30">
          <mxGeometry x="10" y="60" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="33" value="Especialidad" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="30">
          <mxGeometry x="10" y="90" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="34" value="Teléfono" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="30">
          <mxGeometry x="10" y="120" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="35" value="Email" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="30">
          <mxGeometry x="10" y="150" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="36" value="Hospital" style="shape=swimlane;childLayout=stackLayout;horizontal=1;startSize=20;horizontalStack=0;fillColor=#ffffff;swimlaneFillColor=#ffffff;gradientColor=none;swimlaneLine=0;container=1;collapsible=0;" vertex="1" connectable="0" parent="1">
          <mxGeometry x="520" y="60" width="140" height="180" as="geometry" />
        </mxCell>
        <mxCell id="37" value="ID_Hospital" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="36">
          <mxGeometry x="10" y="30" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="38" value="Nombre" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="36">
          <mxGeometry x="10" y="60" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="39" value="Dirección" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="36">
          <mxGeometry x="10" y="90" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="40" value="Teléfono" style="text;html=1;strokeColor=none;fillColor=none;" vertex="1" parent="36">
          <mxGeometry x="10" y="120" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="41" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;" edge="1" parent="1" source="2" target="8">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="42" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;" edge="1" parent="1" source="2" target="13">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="43" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;" edge="1" parent="1" source="8" target="19">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="44" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;" edge="1" parent="1" source="13" target="19">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="45" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;" edge="1" parent="1" source="19" target="30">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="46" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;" edge="1" parent="1" source="19" target="36">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
