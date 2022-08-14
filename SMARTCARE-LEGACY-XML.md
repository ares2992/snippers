# Legacy Fields


## Date

```xml
<field name="KnownPositiveOnArt">
	<ValidationData>
		<ValidationType>String</ValidationType>
		<ProgrammaticType>String</ProgrammaticType>
		<Enumerated AllowOther="No">Yes</Enumerated>
		<IsNullable>Yes</IsNullable>
		<DatabaseDrivenValidation>False</DatabaseDrivenValidation>
		<min />
		<max />
		<warnMin />
		<warnMax />
		<critMin />
		<critMax />
	</ValidationData>
	<ControlName>gbxKnownPositiveOnArt</ControlName>
	<ControlType>RadioGroupBox</ControlType>
	<EnumerationType>
		<item index="0">
			<DisplayName>No</DisplayName>
			<ItemControlName>rdbKnownPositiveOnArtYes</ItemControlName>
		</item>
		<item index="1">
			<DisplayName>Yes</DisplayName>
			<ItemControlName>rdbKnownPositiveOnArtNo</ItemControlName>
		</item>
	</EnumerationType>
	<Storage StorageCall="ClinicalObs">
		<StorageItems>
		<StorageItemType name="Obs" />
		<StorageItemType name="ObsCode" />
		<StorageItemType name="ObsTypeCode" />
		</StorageItems>
	</Storage>
	<ReadableName>Known Positive On Art</ReadableName>
	<ConceptImplementationIDString>not_set</ConceptImplementationIDString>
	<CustomDBLogicRequired>False</CustomDBLogicRequired>
</field>

```
## Combobox
```xml
<field name="ModeOfDelivery">
	<ValidationData>
		<ValidationType>String</ValidationType>
		<ProgrammaticType>String</ProgrammaticType>
		<Enumerated AllowOther="No">Yes</Enumerated>
		<IsNullable>Yes</IsNullable>
		<DatabaseDrivenValidation>False</DatabaseDrivenValidation>
		<min />
		<max />
		<warnMin />
		<warnMax />
		<critMin />
		<critMax />
	</ValidationData>
	<ControlName>cmbModeOdDelivery</ControlName>
	<ControlType>ComboBox</ControlType>
	<EnumerationType>
		<item index="0">
		<DisplayName>SVD</DisplayName>
		</item>
		<item index="1">
		<DisplayName>VAC</DisplayName>
		</item>
		<item index="2">
		<DisplayName>FOR</DisplayName>
		</item>
		<item index="3">
		<DisplayName>CS</DisplayName>
		</item>
		<item index="4">
		<DisplayName>Early Termination</DisplayName>
		</item>
		<item index="5">
		<DisplayName>BRE</DisplayName>
		</item>
	</EnumerationType>
	<Storage StorageCall="ClinicalObs">
		<StorageItems>
			<StorageItemType name="Obs" />
			<StorageItemType name="ObsCode" />
			<StorageItemType name="ObsTypeCode" />
		</StorageItems>
	</Storage>
	<ReadableName>Mode Of Delivery</ReadableName>
	<ConceptImplementationIDString>not_set</ConceptImplementationIDString>
	<CustomDBLogicRequired>False</CustomDBLogicRequired>
	</field>
```

## Radiogroup (Yes/No)
```xml
<field name="Fatigue">
	<ValidationData>
		<ValidationType>String</ValidationType>
		<ProgrammaticType>String</ProgrammaticType>
		<Enumerated AllowOther="No">Yes</Enumerated>
		<IsNullable>Yes</IsNullable>
		<DatabaseDrivenValidation>False</DatabaseDrivenValidation>
		<min />
		<max />
		<warnMin />
		<warnMax />
		<critMin />
		<critMax />
	</ValidationData>
	<ControlName>gbxFatigueYesNo</ControlName>
	<ControlType>RadioGroupBox</ControlType>
	<EnumerationType>
		<item index="0">
		<DisplayName>No</DisplayName>
		<ItemControlName>rbFatigueNo</ItemControlName>
		</item>
		<item index="1">
		<DisplayName>Yes</DisplayName>
		<ItemControlName>rbFatigueYes</ItemControlName>
		</item>
	</EnumerationType>
	<Storage StorageCall="ClinicalObs">
		<StorageItems>
		<StorageItemType name="Obs" />
		<StorageItemType name="ObsCode" />
		<StorageItemType name="ObsTypeCode" />
		</StorageItems>
	</Storage>
	<ReadableName>Fatigue</ReadableName>
	<ConceptImplementationIDString>not_set</ConceptImplementationIDString>
	<CustomDBLogicRequired>False</CustomDBLogicRequired>
</field>
```

## Textbox
```xml
<field name="ViralLoadWithinFourWeeks">
	<ValidationData>
		<ValidationType>String</ValidationType>
		<ProgrammaticType>String</ProgrammaticType>
		<Enumerated AllowOther="No">No</Enumerated>
		<IsNullable>Yes</IsNullable>
		<DatabaseDrivenValidation>False</DatabaseDrivenValidation>
		<min />
		<max />
		<warnMin />
		<warnMax />
		<critMin />
		<critMax />
	</ValidationData>
	<ControlName>txtViralLoadWithinFourWeeks</ControlName>
	<ControlType>TextBox</ControlType>
	<Storage StorageCall="ClinicalObs">
		<StorageItems>
		<StorageItemType name="Obs" />
		<StorageItemType name="ObsCode" />
		<StorageItemType name="ObsTypeCode" />
		</StorageItems>
	</Storage>
	<ReadableName>Viral Load Within Four Weeks</ReadableName>
	<ConceptImplementationIDString>not_set</ConceptImplementationIDString>
	<CustomDBLogicRequired>False</CustomDBLogicRequired>
</field>
```
## Checkbox Group
```xml
 <field name="Referrals">
	<ValidationData>
		<ValidationType>EnumerationArray</ValidationType>
		<ProgrammaticType>EnumerationArray</ProgrammaticType>
		<Enumerated AllowOther="No">Yes</Enumerated>
		<IsNullable>Yes</IsNullable>
		<DatabaseDrivenValidation>False</DatabaseDrivenValidation>
		<min />
		<max />
		<warnMin />
		<warnMax />
		<critMin />
		<critMax />
	</ValidationData>
	<ControlName>gbxReferrals</ControlName>
	<ControlType>CheckGroupBox</ControlType>
	<EnumerationType>
		<item index="0">
		<DisplayName>Consented to HBC</DisplayName>
		<ItemControlName>cbxConsentedToHBC</ItemControlName>
		</item>
		<item index="1">
		<DisplayName>Adherence counseling</DisplayName>
		<ItemControlName>cbxAdherenceCounseling</ItemControlName>
		</item>
	</EnumerationType>
	<Storage StorageCall="ClinicalObs">
		<StorageItems>
		<StorageItemType name="Obs" />
		<StorageItemType name="ObsCode" />
		<StorageItemType name="ObsTypeCode" />
		</StorageItems>
	</Storage>
	<ReadableName>Referrals</ReadableName>
	<ConceptImplementationIDString>not_set</ConceptImplementationIDString>
	<CustomDBLogicRequired>False</CustomDBLogicRequired>
    </field>
```


## Control Type
```xml

```







