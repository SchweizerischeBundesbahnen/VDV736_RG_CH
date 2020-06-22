# VDV736_RG_CH
This repository documents the API usage for the Swiss Siri SX data interchange.

## Siri/VDV 736 ServiceDelivery		
Each Siri SX field listed below can be delivered in a ServiceDelivery message. <br>
However, there are fields that are marked to be ignored (see column CH RG Usage) because their usage is not yet expected. <br>
Please consider that information can be lost / will probably not be processed by some systems if using these "ignore" fields. 

<table>
    <tr>
        <th colspan="4">Field name</th>
        <th>Field type</th>
        <th>SIRI SX Usage</th>
        <th>VDV 736 Usage</th>
        <th>CH RG Usage</th>
        <th>CH RG Format</th>
        <th>CH RG Default</th>
        <th>Siri / VDV736 Remarks</th>
        <th>CH RG Remarks</th>
        <th>CH RG Example</th>
        <th>EMS SKI relevant</th>
        <th>Similar VDV 453/454 Element</th>
    </tr>
    <tr>
        <td colspan="4">ServiceDelivery</td>
        <td>+Structure</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td colspan="3">srsName</td>
        <td>Element</td>
        <td>0:1</td>
        <td>Orig</td>
        <td>Not</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td colspan="3">ResponseTimestamp</td>
        <td>Element</td>
        <td>1:1</td>
        <td>Orig</td>
        <td>1:1</td>
        <td>xsd:dateTime</td>
        <td>Time individual response element was created.</td>
        <td></td>
        <td></td>
        <td>2020-03-08T14:45:40+01:00 <br> 2020-03-19T16:18:00Z</td>
        <td></td>
        <td>AboAnfrage > Zst</td>
    </tr>
</table>
