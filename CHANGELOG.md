# Changelog

## Branch model 

### Branch UmS-XSD-PoC
The branch UmS-XSD-PoC is based on the UmS Standard.  
https://github.com/VDVde/UMS/commit/34a0142abceec5659f3ae1f52e4ec6de1184fbb9

Changes on the standard have to be approved by KIDS (current Project VDV736 Techausschuss) 
and discussed with the UmS group.

The realisation guide for the Swiss UmS implementation is documented here. 

### Branch integration
Our long term goal is that the UmS standard become a subset of Siri. 
For this, we work on changes in the UmS standard (branch integration).  

Based on Siri https://github.com/SIRI-CEN/SIRI/commit/46a470f9cf4836fb70873a0abfe29f6641ba0f9c

## Changes

<br/> 



<table>
    <tr>
        <th>CR-ID</th>
        <th>Description</th>
        <th>Status XSD</th>
        <th>Status KIDS</th>
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
        <td>Default value from attribute version in SituationExchangeDelivery set to 2.1_VDV1.0 instead of 2.0</td>
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
        <td>CountryRef renamed to Country in SituationSourceStructure / Type set to ifopt:CountryRefStructure for Siri compability</td>
        <td>TBD</td>
        <td></td>
        <td>VDV CR to do</td>
        <td>-</td>
        <td></td>
    </tr>
    <tr>
        <td>vdv20200623-02</td>
        <td>Cardinality change in CountryRef (SituationSourceStructure) 1.1 instead of 0.1 </td>
        <td>XSD changed</td>
        <td>reviewed</td>
        <td>known difference to Siri</td>
        <td>-</td>
        <td></td>
    </tr>
    <tr>
        <td>vdv20200623-03</td>
        <td>Cardinality change: Progress 1.1 instead of 0.1 -> Because of default value the field hasn't to be mandatory</td>
        <td>XSD changed</td>
        <td>reviewed</td>
        <td>VDV CR to do</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>ch20200623-07</td>
        <td>Type ClosedTimestampRangeStructure instead of HalfOpenTimestampOutputRangeStructure in ValidityPeriod/PublicationWindow in PtSituationElementStructure (Endtime in HalfOpenTimestampOutputRangeStructure set mandatory temporarly)</td>
        <td>XSD changed</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>vdv20200623-05</td>
        <td>Rename AlertCause to TpegReason for Siri compability</td>
        <td>TBD</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
     <tr>
         <td>ch20200710-02</td>
         <td>Cardinality change of element ReasonName to 0.n</td>
         <td>Doc-only change</td>
         <td></td>
         <td></td>
         <td></td>
         <td></td>
     </tr>
     <tr>
          <td>vdv20200623-07</td>
          <td>PriorityEnumeration created</td>
          <td>TBD</td>
          <td></td>
          <td>VDV-CR to do</td>
          <td></td>
          <td></td>
      </tr>    
      <tr>
        <td>vdv20200703-01</td>
        <td>Cardinality change: Priority in ClassifierGroup from 0.1 to 1.1</td>
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
        <td>Cardinality change: OperatorRef in AffectedOperatorStructure from 1.1 to 0.1</td>
        <td>TBD</td>
        <td></td>
        <td>VDV-CR to do</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>ch20200626-01</td>
        <td>Cardinality change: StopPointRef in AffectedStopPointStructure from 0.1 to 1.1</td>
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
            <td>vdv20200630-06</td>
            <td>VehicleModesOfTransportEnumeration changed</td>
            <td>Wait for Siri</td>
            <td></td>
            <td>Siri CR-016</td>
            <td></td>
        </tr>
        <tr>
            <td>vdv20200630-06</td>
            <td>Integrate UmS PublishingAction in Siri</td>
            <td>Wait for Siri</td>
            <td></td>
            <td>Siri CR-069</td>
            <td></td>
        </tr>
        <tr>
             <td>ch20200710-03</td>
             <td>Cardinality change: DirectionRef in AffectedLineStructure from 0.1 to 1.1</td>
             <td>Doc-only change</td>
             <td></td>
             <td></td>
             <td></td>
             <td></td>
         </tr>
         <tr>     
        <td>vdv20200630-06</td>
        <td>DefaultedTextStructure extension changed to NaturalLanguageStringStructure for Siri compability</td>
         <td>XSD changed</td>
         <td></td>
         <td>VDV CR to do</td>
         <td></td>
         <td></td>
     </tr>
        
</table>

