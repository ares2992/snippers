# Legacy Fields


## Data

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
						<ConceptImplementationIDString>known_positive_on_art</ConceptImplementationIDString>
						<CustomDBLogicRequired>False</CustomDBLogicRequired>
</field>
```
