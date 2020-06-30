# Changelog
Initiale Version basierend auf https://github.com/SIRI-CEN/SIRI/commit/46a470f9cf4836fb70873a0abfe29f6641ba0f9c

## CH-RG Changelog
- ch20200623-01: Kardinalität von SituationExchangeDelivery von 1.n auf 1.1 gesetzt 
- ch20200623-02: Sprachregion abbilden / Gross und Kleinschreibung der Sprache ermöglichen https://issues.sbb.ch/browse/UMS-171
- ch20200623-03: Situations Kardinalität 1.1 statt 0.1 
- ch20200623-04: PtSituationElement Kardinalität 1.n statt 0.n
- ch20200623-05: Format SituationNumber beschrieben
- ch20200623-06: SituationVersion Range gesetzt
- ch20200623-08: Default undefinedAlertCause gesetzt 
- ch20200623-09: MaxLength PopulatedStringType gesetzt
- ch20200626-01: StopPointRef in AffectedStopPointStructure Kardinalität 1.1 statt 0.1
- ch20200626-02: OperatorRef in AffectedOperatorStructure Kardinalität 1.1 statt 0.1
- ch20200630-01: Format ParticipantRefStructure / OperatorRefStructure/ LineRef/ StopPointRef/DirectionRef/OrganisationRefStructure beschrieben
- ch20200630-02: Attribut version in SituationExchangeDelivery Default auf 2.1_VDV1.0 angepasst 


TODO
- ch20200623-02: Sprachregion abbilden / Gross und Kleinschreibung der Sprache ermöglichen https://issues.sbb.ch/browse/UMS-171
- ch20200630-01: Examples fehlen
- ch20200623-09: MaxLength per Feld gemäss Conf-Vorlage unterscheiden

Reverted 
- ch20200623-07: ClosedTimestampRangeStructure statt HalfOpenTimestampOutputRangeStructure in ValidityPeriod/PublicationWindow auf Situation-Ebene

## VDV736 Changelog
Entspricht VDV736 1.0 <br/>
- vdv20200623-01: CountryRef/ParticipantRef in SituationBaseIdentityGroup Kardinalität 1.1 statt 0.1
- vdv20200623-02: CountryRef in SituationSourceStructure Kardinalität 1.1 statt 0.1
- vdv20200623-04: ValidityPeriod als innerhalb eines PublicationWindows beschrieben
- vdv20200623-06: Attribut xml:lang als required markiert
- vdv20200623-07: PriorityEnumeration erstellt, Kardinalität von 0.1 auf 1.1 gesetzt auf Situation-Ebene 
- vdv20200626-02: StopPlaceRef / StopPlaceName in AffectedStopPointStructure hinzugefügt
- vdv20200626-03: Not-Values in VehicleModesOfTransportEnumeration auskommentiert
- vdv20200630-01: Endtime Kardinalität 1.1 statt 0.1 in HalfOpenTimestampOutputRangeStructure
- vdv20200630-02: Lines in AffectedStopPointStructure hinzugefügt
- vdv20200630-03: StopPoints und StopPlaces in AffectedLineStructure hinzugefügt

Reverted
- vdv20200623-03: Progress Kardinalität 1.1 statt 0.1 -> Default auswerten reicht               
- vdv20200623-05: AlertCause Element eingefügt -> in Siri führt das Element TpegReason Pts38

Weitere Änderungen seit letzter Schriftpublikation:
- vdv20200626-01: RoutePointTypeEnumeration angepasst

## Siri Changelog
Entspricht Siri 2.1 <br/>
Letzter Abgleich am 23.06.2020 basierend auf https://github.com/SIRI-CEN/SIRI/commit/3f24da28d0b049b5bb7451b23b618c8c60694e31




