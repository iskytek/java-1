

# V1beta1VolumeAttachmentSpec

VolumeAttachmentSpec is the specification of a VolumeAttachment request.
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**attacher** | **String** | Attacher indicates the name of the volume driver that MUST handle this request. This is the name returned by GetPluginName(). | 
**nodeName** | **String** | The node that the volume should be attached to. | 
**source** | [**V1beta1VolumeAttachmentSource**](V1beta1VolumeAttachmentSource.md) |  | 



