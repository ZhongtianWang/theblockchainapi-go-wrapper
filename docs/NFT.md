# NFT

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**NFTData**](NFTData.md) |  | [optional] 
**IsMutable** | Pointer to **bool** |  | [optional] 
**Mint** | Pointer to **string** | The public key address of the NFT  | [optional] 
**PrimarySaleHappened** | Pointer to **bool** |  | [optional] 
**UpdateAuthority** | Pointer to **string** | A public key address that is usually that of the person who minted the NFT  | [optional] 
**SellerFeeBasisPoints** | Pointer to **float32** |  | [optional] 
**MintSecretRecoveryPhrase** | Pointer to **string** |  | [optional] 
**ExplorerUrl** | Pointer to **string** |  | [optional] 

## Methods

### NewNFT

`func NewNFT() *NFT`

NewNFT instantiates a new NFT object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNFTWithDefaults

`func NewNFTWithDefaults() *NFT`

NewNFTWithDefaults instantiates a new NFT object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *NFT) GetData() NFTData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *NFT) GetDataOk() (*NFTData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *NFT) SetData(v NFTData)`

SetData sets Data field to given value.

### HasData

`func (o *NFT) HasData() bool`

HasData returns a boolean if a field has been set.

### GetIsMutable

`func (o *NFT) GetIsMutable() bool`

GetIsMutable returns the IsMutable field if non-nil, zero value otherwise.

### GetIsMutableOk

`func (o *NFT) GetIsMutableOk() (*bool, bool)`

GetIsMutableOk returns a tuple with the IsMutable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsMutable

`func (o *NFT) SetIsMutable(v bool)`

SetIsMutable sets IsMutable field to given value.

### HasIsMutable

`func (o *NFT) HasIsMutable() bool`

HasIsMutable returns a boolean if a field has been set.

### GetMint

`func (o *NFT) GetMint() string`

GetMint returns the Mint field if non-nil, zero value otherwise.

### GetMintOk

`func (o *NFT) GetMintOk() (*string, bool)`

GetMintOk returns a tuple with the Mint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMint

`func (o *NFT) SetMint(v string)`

SetMint sets Mint field to given value.

### HasMint

`func (o *NFT) HasMint() bool`

HasMint returns a boolean if a field has been set.

### GetPrimarySaleHappened

`func (o *NFT) GetPrimarySaleHappened() bool`

GetPrimarySaleHappened returns the PrimarySaleHappened field if non-nil, zero value otherwise.

### GetPrimarySaleHappenedOk

`func (o *NFT) GetPrimarySaleHappenedOk() (*bool, bool)`

GetPrimarySaleHappenedOk returns a tuple with the PrimarySaleHappened field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimarySaleHappened

`func (o *NFT) SetPrimarySaleHappened(v bool)`

SetPrimarySaleHappened sets PrimarySaleHappened field to given value.

### HasPrimarySaleHappened

`func (o *NFT) HasPrimarySaleHappened() bool`

HasPrimarySaleHappened returns a boolean if a field has been set.

### GetUpdateAuthority

`func (o *NFT) GetUpdateAuthority() string`

GetUpdateAuthority returns the UpdateAuthority field if non-nil, zero value otherwise.

### GetUpdateAuthorityOk

`func (o *NFT) GetUpdateAuthorityOk() (*string, bool)`

GetUpdateAuthorityOk returns a tuple with the UpdateAuthority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdateAuthority

`func (o *NFT) SetUpdateAuthority(v string)`

SetUpdateAuthority sets UpdateAuthority field to given value.

### HasUpdateAuthority

`func (o *NFT) HasUpdateAuthority() bool`

HasUpdateAuthority returns a boolean if a field has been set.

### GetSellerFeeBasisPoints

`func (o *NFT) GetSellerFeeBasisPoints() float32`

GetSellerFeeBasisPoints returns the SellerFeeBasisPoints field if non-nil, zero value otherwise.

### GetSellerFeeBasisPointsOk

`func (o *NFT) GetSellerFeeBasisPointsOk() (*float32, bool)`

GetSellerFeeBasisPointsOk returns a tuple with the SellerFeeBasisPoints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSellerFeeBasisPoints

`func (o *NFT) SetSellerFeeBasisPoints(v float32)`

SetSellerFeeBasisPoints sets SellerFeeBasisPoints field to given value.

### HasSellerFeeBasisPoints

`func (o *NFT) HasSellerFeeBasisPoints() bool`

HasSellerFeeBasisPoints returns a boolean if a field has been set.

### GetMintSecretRecoveryPhrase

`func (o *NFT) GetMintSecretRecoveryPhrase() string`

GetMintSecretRecoveryPhrase returns the MintSecretRecoveryPhrase field if non-nil, zero value otherwise.

### GetMintSecretRecoveryPhraseOk

`func (o *NFT) GetMintSecretRecoveryPhraseOk() (*string, bool)`

GetMintSecretRecoveryPhraseOk returns a tuple with the MintSecretRecoveryPhrase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMintSecretRecoveryPhrase

`func (o *NFT) SetMintSecretRecoveryPhrase(v string)`

SetMintSecretRecoveryPhrase sets MintSecretRecoveryPhrase field to given value.

### HasMintSecretRecoveryPhrase

`func (o *NFT) HasMintSecretRecoveryPhrase() bool`

HasMintSecretRecoveryPhrase returns a boolean if a field has been set.

### GetExplorerUrl

`func (o *NFT) GetExplorerUrl() string`

GetExplorerUrl returns the ExplorerUrl field if non-nil, zero value otherwise.

### GetExplorerUrlOk

`func (o *NFT) GetExplorerUrlOk() (*string, bool)`

GetExplorerUrlOk returns a tuple with the ExplorerUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExplorerUrl

`func (o *NFT) SetExplorerUrl(v string)`

SetExplorerUrl sets ExplorerUrl field to given value.

### HasExplorerUrl

`func (o *NFT) HasExplorerUrl() bool`

HasExplorerUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


