# Produksjonsplass

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifikasjonsnummer** | **string** | en identifikasjon som du bruker for å finne fram denne enheten/identiteten i ditt system, også kalt identifikasjonsnummer i andre systemer | 
**Identifikasjonstypekode** | **string** | for å kunne støtte flere kilder må man kunne gjennbruke informasjonsnummer for hver kilde, også kalt identifikasjontypeKode i andre systemer | 
**Point** | Pointer to **string** | string representasjon av SDO_UTIL.TO_WKTGEOMETRY | [optional] 
**Koordinatsystem** | Pointer to **string** | koordinatsystem som skal brukes for å representere point, mest typisk er 25833 | [optional] 
**GeomMaster** | Pointer to **string** | hvor dataene fra, ikke hvor kilden er, men f.eks mats selvom kilden er matrikkel | [optional] 
**GeomKilde** | Pointer to **string** | hvor kommer dataene opprinnelig fra, i.e., matrikkel, slf, brreg, osv | [optional] 

## Methods

### NewProduksjonsplass

`func NewProduksjonsplass(identifikasjonsnummer string, identifikasjonstypekode string, ) *Produksjonsplass`

NewProduksjonsplass instantiates a new Produksjonsplass object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProduksjonsplassWithDefaults

`func NewProduksjonsplassWithDefaults() *Produksjonsplass`

NewProduksjonsplassWithDefaults instantiates a new Produksjonsplass object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifikasjonsnummer

`func (o *Produksjonsplass) GetIdentifikasjonsnummer() string`

GetIdentifikasjonsnummer returns the Identifikasjonsnummer field if non-nil, zero value otherwise.

### GetIdentifikasjonsnummerOk

`func (o *Produksjonsplass) GetIdentifikasjonsnummerOk() (*string, bool)`

GetIdentifikasjonsnummerOk returns a tuple with the Identifikasjonsnummer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifikasjonsnummer

`func (o *Produksjonsplass) SetIdentifikasjonsnummer(v string)`

SetIdentifikasjonsnummer sets Identifikasjonsnummer field to given value.


### GetIdentifikasjonstypekode

`func (o *Produksjonsplass) GetIdentifikasjonstypekode() string`

GetIdentifikasjonstypekode returns the Identifikasjonstypekode field if non-nil, zero value otherwise.

### GetIdentifikasjonstypekodeOk

`func (o *Produksjonsplass) GetIdentifikasjonstypekodeOk() (*string, bool)`

GetIdentifikasjonstypekodeOk returns a tuple with the Identifikasjonstypekode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifikasjonstypekode

`func (o *Produksjonsplass) SetIdentifikasjonstypekode(v string)`

SetIdentifikasjonstypekode sets Identifikasjonstypekode field to given value.


### GetPoint

`func (o *Produksjonsplass) GetPoint() string`

GetPoint returns the Point field if non-nil, zero value otherwise.

### GetPointOk

`func (o *Produksjonsplass) GetPointOk() (*string, bool)`

GetPointOk returns a tuple with the Point field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPoint

`func (o *Produksjonsplass) SetPoint(v string)`

SetPoint sets Point field to given value.

### HasPoint

`func (o *Produksjonsplass) HasPoint() bool`

HasPoint returns a boolean if a field has been set.

### GetKoordinatsystem

`func (o *Produksjonsplass) GetKoordinatsystem() string`

GetKoordinatsystem returns the Koordinatsystem field if non-nil, zero value otherwise.

### GetKoordinatsystemOk

`func (o *Produksjonsplass) GetKoordinatsystemOk() (*string, bool)`

GetKoordinatsystemOk returns a tuple with the Koordinatsystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKoordinatsystem

`func (o *Produksjonsplass) SetKoordinatsystem(v string)`

SetKoordinatsystem sets Koordinatsystem field to given value.

### HasKoordinatsystem

`func (o *Produksjonsplass) HasKoordinatsystem() bool`

HasKoordinatsystem returns a boolean if a field has been set.

### GetGeomMaster

`func (o *Produksjonsplass) GetGeomMaster() string`

GetGeomMaster returns the GeomMaster field if non-nil, zero value otherwise.

### GetGeomMasterOk

`func (o *Produksjonsplass) GetGeomMasterOk() (*string, bool)`

GetGeomMasterOk returns a tuple with the GeomMaster field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeomMaster

`func (o *Produksjonsplass) SetGeomMaster(v string)`

SetGeomMaster sets GeomMaster field to given value.

### HasGeomMaster

`func (o *Produksjonsplass) HasGeomMaster() bool`

HasGeomMaster returns a boolean if a field has been set.

### GetGeomKilde

`func (o *Produksjonsplass) GetGeomKilde() string`

GetGeomKilde returns the GeomKilde field if non-nil, zero value otherwise.

### GetGeomKildeOk

`func (o *Produksjonsplass) GetGeomKildeOk() (*string, bool)`

GetGeomKildeOk returns a tuple with the GeomKilde field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeomKilde

`func (o *Produksjonsplass) SetGeomKilde(v string)`

SetGeomKilde sets GeomKilde field to given value.

### HasGeomKilde

`func (o *Produksjonsplass) HasGeomKilde() bool`

HasGeomKilde returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


