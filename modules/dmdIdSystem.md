## DMD ID User ID Submodule

For assistance setting up your module please contact us at [prebid@dmdconnects.com](mailto:prebid@dmdconnects.com).

### Prebid Params

Individual params may be set for the DMD ID Submodule.
```
pbjs.setConfig({
    userSync: {
        userIds: [{
            name: 'dmdId',
        }]
    }
});
```

## Parameter Descriptions for the `userSync` Configuration Section
The below parameters apply only to the DMD ID integration.

{: .table .table-bordered .table-striped }
| Param under userSync.userIds[] | Scope | Type | Description | Example |
| --- | --- | --- | --- | --- |
| name | Required | String | The name of Module | `"dmdId"` |
| params | Required | Object | Container of all module params. |  |
| params.partnerId | Required | String | This is your `partnerId` as provided by DMD Marketing Corp. | `123-45-67AK89` |
