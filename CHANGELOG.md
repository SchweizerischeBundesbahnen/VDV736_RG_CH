# Changelog
Initiale Version basierend auf https://github.com/VDVde/UMS/commit/34a0142abceec5659f3ae1f52e4ec6de1184fbb9

<table>
    <tr>
        <th>CR-ID</th>
        <th>Beschreibung</th>
        <th>Status</th>
        <th>Status Techausschuss</th>
        <th>Status VDV736</th>
        <th>Status Siri</th>
        <th>Jira</th>        
    </tr>
    <tr>
        <td>ch20200623-01</td>
        <td>Cardinality from SituationExchangeDelivery changed from 1.n to 1.1</td>
        <td>XSD changed</td>
        <td>reviewed</td>
        <td>VDV-CR to do</td>
        <td>TBD</td>
        <td></td>
    </tr>
    <tr>
        <td>ch20200630-02</td>
        <td>Default value from attribute version in SituationExchangeDelivery set to 2.1_VDV1.0</td>
        <td>not relevant yet</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>vdv20200623-01</td>
        <td>Cardinality CountryRef/ParticipantRef in SituationBaseIdentityGroup 1.1 instead of 0.1</td>
        <td>XSD changed</td>
        <td>reviewed</td>
        <td>known difference to Siri</td>
        <td>-</td>
        <td></td>
    </tr>    
    <tr>
        <td>vdv20200630-05</td>
        <td>Cardinality from version in SituationUpdateIdentityGroup changed from 0.1 to 1.1</td>
        <td>XSD changed</td>
        <td>reviewed</td>
        <td>known difference to Siri</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>vdv20200710-01</td>
        <td>Cardinality from UpdateCountryRef/UpdateParticipantRef in SituationUpdateIdentityGroup changed from 1.1 to 0.1</td>
        <td>Doc-only change</td>
        <td>reviewed</td>
        <td></td>
        <td>-</td>
        <td></td>
    </tr>
    <tr>
        <td>vdv20200630-04</td>
        <td>CountryRef zu Country umbenennen in SituationSourceStructure / Type set to ifopt:CountryRefStructure (Siri-Kompabilität)</td>
        <td>TBD</td>
        <td></td>
        <td>VDV CR to do</td>
        <td>-</td>
        <td></td>
    </tr>
    <tr>
        <td>vdv20200623-02</td>
        <td>Cardinality CountryRef in SituationSourceStructure 1.1 instead of 0.1 </td>
        <td>XSD changed</td>
        <td>reviewed</td>
        <td>known difference to Siri</td>
        <td>-</td>
        <td></td>
    </tr>
    <tr>
        <td>vdv20200623-03</td>
        <td>Progress Kardinalität 1.1 statt 0.1 -> Default auswerten reicht</td>
        <td>XSD changed</td>
        <td>reviewed</td>
        <td>VDV CR to do</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>ch20200623-07</td>
        <td>ClosedTimestampRangeStructure statt HalfOpenTimestampOutputRangeStructure in ValidityPeriod/PublicationWindow auf Situation-Ebene (temporär Endtime in HalfOpenTimestampOutputRangeStructure 1.1 gesetzt)</td>
        <td>XSD changed</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>vdv20200623-05</td>
        <td>Change VDV736 element name from AlertCause to TpegReason for Siri compability</td>
        <td>TBD</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
     <tr>
         <td>ch20200710-02</td>
         <td>Cardinality of ReasonName change to 0.n</td>
         <td>Doc-only change</td>
         <td></td>
         <td></td>
         <td></td>
         <td></td>
     </tr>
     <tr>
          <td>vdv20200623-07</td>
          <td>PriorityEnumeration erstellt</td>
          <td>TBD</td>
          <td></td>
          <td>VDV-CR to do</td>
          <td></td>
          <td></td>
      </tr>    
      <tr>
        <td>vdv20200703-01</td>
        <td>Cardinality Priority in ClassifierGroup changed from 0.1 to 1.1</td>
        <td>XSD changed</td>
        <td></td>
        <td>VDV-CR to do</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>vdv20200702-01</td>
        <td>ScopeTypeEnumeration changed</td>
        <td>TBD</td>
        <td></td>
        <td></td>
        <td>Siri CR-015</td>
        <td></td>
    </tr>
    <tr>
        <td>ch20200626-02</td>
        <td>Cardinality from OperatorRef in AffectedOperatorStructure changed from 1.1 to 0.1</td>
        <td>TBD</td>
        <td></td>
        <td>VDV-CR to do</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>ch20200626-01</td>
        <td>Cardinality from StopPointRef in AffectedStopPointStructure changed from 0.1 to 1.1</td>
        <td>TBD</td>
        <td></td>
        <td></td>
        <td>VDV-CR to do</td>
        <td></td>
    </tr>
    <tr>
        <td>vdv20200626-01</td>
        <td>RoutePointTypeEnumeration changed</td>
        <td>TBD</td>
        <td></td>
        <td>Siri CR-015</td>
        <td></td>
    </tr>
    <tr>
            <td>vdv20200626-01</td>
            <td>RoutePointTypeEnumeration changed</td>
            <td>TBD</td>
            <td></td>
            <td>Siri CR-015</td>
            <td></td>
        </tr>
    <tr>
         <td>ch20200710-03</td>
         <td>Cardinality from DirectionRef in AffectedLineStructure changed from 0.1 to 1.1</td>
         <td>Doc-only change</td>
         <td></td>
         <td></td>
         <td></td>
         <td></td>
     </tr>
     <tr>     
        <td>vdv20200630-06</td>
        <td>DefaultedTextStructure extends auf NaturalLanguageStringStructure analog zu Siri</td>
         <td>XSD changed</td>
         <td></td>
         <td>VDV CR to do</td>
         <td></td>
         <td></td>
     </tr>
        
</table>

