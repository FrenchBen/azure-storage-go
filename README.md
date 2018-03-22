# Disclaimer
This is not affiliated with anything Azure is doing, nor is it the proper copy of the original Azure/azure-storage-go package.
An issue has been filed to express the lack of care from Azure with Go developers and the use of their package. Issue can be found here:
https://github.com/Azure/azure-storage-blob-go/issues/35

Hopefully this will be resolved soon, and this package can then be removed. Meanwhile I'll keep it here for all of the broken libraries out there to use. 




# Azure Storage SDK for Go (Preview)

:exclamation: IMPORTANT: This package is in maintenance only and will be deprecated in the
future. Consider using the new package for blobs currently in preview at
[github.com/Azure/azure-storage-blob-go](https://github.com/Azure/azure-storage-blob-go).
New Table, Queue and File packages are also in development.

The `github.com/Azure/azure-sdk-for-go/storage` package is used to manage
[Azure Storage](https://docs.microsoft.com/en-us/azure/storage/) data plane
resources: containers, blobs, tables, and queues.

To manage storage *accounts* use Azure Resource Manager (ARM) via the packages
at [github.com/Azure/azure-sdk-for-go/services/storage](https://github.com/Azure/azure-sdk-for-go/tree/master/services/storage).

This package also supports the [Azure Storage
Emulator](https://azure.microsoft.com/documentation/articles/storage-use-emulator/)
(Windows only).

