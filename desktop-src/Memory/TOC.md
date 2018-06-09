# [Memory Management](memory-management.md)
## [About Memory Management](about-memory-management.md)
### [Virtual Address Space](virtual-address-space.md)
#### [Virtual Address Space and Physical Storage](virtual-address-space-and-physical-storage.md)
#### [Working Set](working-set.md)
#### [Page State](page-state.md)
#### [Scope of Allocated Memory](scope-of-allocated-memory.md)
#### [Data Execution Prevention](data-execution-prevention.md)
#### [Memory Protection](memory-protection.md)
#### [Memory Limits for Windows and Windows Server Releases](memory-limits-for-windows-releases.md)
### [Memory Pools](memory-pools.md)
### [Memory Performance Information](memory-performance-information.md)
### [Virtual Memory Functions](virtual-memory-functions.md)
#### [Allocating Virtual Memory](allocating-virtual-memory.md)
#### [Freeing Virtual Memory](freeing-virtual-memory.md)
#### [Working with Pages](working-with-pages.md)
### [Heap Functions](heap-functions.md)
#### [Low-fragmentation Heap](low-fragmentation-heap.md)
### [File Mapping](file-mapping.md)
#### [Creating a File Mapping Object](creating-a-file-mapping-object.md)
#### [Creating a File View](creating-a-file-view.md)
#### [Sharing Files and Memory](sharing-files-and-memory.md)
#### [Reading and Writing From a File View](reading-and-writing-from-a-file-view.md)
#### [Closing a File Mapping Object](closing-a-file-mapping-object.md)
#### [File Mapping Security and Access Rights](file-mapping-security-and-access-rights.md)
### [Large Memory Support](large-memory-support.md)
#### [4-Gigabyte Tuning: BCDEdit and Boot.ini](4-gigabyte-tuning.md)
#### [Physical Address Extension](physical-address-extension.md)
#### [Address Windowing Extensions](address-windowing-extensions.md)
#### [Large-Page Support](large-page-support.md)
### [Global and Local Functions](global-and-local-functions.md)
### [Standard C Library Functions](standard-c-library-functions.md)
### [Comparing Memory Allocation Methods](comparing-memory-allocation-methods.md)
## [Using the Memory Management Functions](using-the-memory-management-functions.md)
### [Reserving and Committing Memory](reserving-and-committing-memory.md)
### [Creating Guard Pages](creating-guard-pages.md)
### [Enumerating a Heap](enumerating-a-heap.md)
### [Getting Process Heaps](getting-process-heaps.md)
### [Using File Mapping](using-file-mapping.md)
#### [Creating a View Within a File](creating-a-view-within-a-file.md)
#### [Creating Named Shared Memory](creating-named-shared-memory.md)
#### [Creating a File Mapping Using Large Pages](creating-a-file-mapping-using-large-pages.md)
#### [Obtaining a File Name From a File Handle](obtaining-a-file-name-from-a-file-handle.md)
### [AWE Example](awe-example.md)
### [Allocating Memory from a NUMA Node](allocating-memory-from-a-numa-node.md)
## [Memory Management Reference](memory-management-reference.md)
### [Memory Management Enumerations](memory-management-enumerations.md)
#### [HEAP_INFORMATION_CLASS](/windows/desktop/api/WinNT/ne-winnt-_heap_information_class)
### [Memory Management Functions](memory-management-functions.md)
#### [AddSecureMemoryCacheCallback](/windows/desktop/api/WinBase/nf-winbase-addsecurememorycachecallback)
#### [AllocateUserPhysicalPages](https://msdn.microsoft.com/en-us/library/Aa366528(v=VS.85).aspx)
#### [AllocateUserPhysicalPagesNuma](https://msdn.microsoft.com/en-us/library/Aa366529(v=VS.85).aspx)
#### [BadMemoryCallbackRoutine](/windows/desktop/api/WinBase/)
#### [CopyMemory](/windows/desktop/api/WinBase/)
#### [CreateFileMapping](/windows/desktop/api/WinBase/nf-winbase-createfilemappinga)
#### [CreateFileMappingFromApp](/windows/desktop/api/MemoryApi/nf-memoryapi-createfilemappingfromapp)
#### [CreateFileMappingNuma](/windows/desktop/api/WinBase/nf-winbase-createfilemappingnumaa)
#### [CreateMemoryResourceNotification](https://msdn.microsoft.com/en-us/library/Aa366541(v=VS.85).aspx)
#### [DiscardVirtualMemory](https://msdn.microsoft.com/en-us/library/Dn781432(v=VS.85).aspx)
#### [FillMemory](https://msdn.microsoft.com/en-us/library/Aa366561(v=VS.85).aspx)
#### [FlushViewOfFile](https://msdn.microsoft.com/en-us/library/Aa366563(v=VS.85).aspx)
#### [FreeUserPhysicalPages](https://msdn.microsoft.com/en-us/library/Aa366566(v=VS.85).aspx)
#### [GetLargePageMinimum](https://msdn.microsoft.com/en-us/library/Aa366568(v=VS.85).aspx)
#### [GetMemoryErrorHandlingCapabilities](https://msdn.microsoft.com/en-us/library/Hh691012(v=VS.85).aspx)
#### [GetPhysicallyInstalledSystemMemory](/windows/desktop/api/WinBase/)
#### [GetProcessDEPPolicy](/windows/desktop/api/WinBase/nf-winbase-getprocessdeppolicy)
#### [GetProcessHeap](/windows/desktop/api/HeapApi/nf-heapapi-getprocessheap)
#### [GetProcessHeaps](/windows/desktop/api/HeapApi/nf-heapapi-getprocessheaps)
#### [GetSystemDEPPolicy](/windows/desktop/api/WinBase/nf-winbase-getsystemdeppolicy)
#### [GetSystemFileCacheSize](https://msdn.microsoft.com/en-us/library/Aa965224(v=VS.85).aspx)
#### [GetWriteWatch](https://msdn.microsoft.com/en-us/library/Aa366573(v=VS.85).aspx)
#### [GlobalAlloc](/windows/desktop/api/WinBase/nf-winbase-globalalloc)
#### [GlobalDiscard](/windows/desktop/api/WinBase/nf-winbase-globaldiscard)
#### [GlobalFlags](/windows/desktop/api/WinBase/nf-winbase-globalflags)
#### [GlobalFree](/windows/desktop/api/WinBase/nf-winbase-globalfree)
#### [GlobalHandle](/windows/desktop/api/WinBase/nf-winbase-globalhandle)
#### [GlobalLock](/windows/desktop/api/WinBase/nf-winbase-globallock)
#### [GlobalMemoryStatus](/windows/desktop/api/WinBase/nf-winbase-globalmemorystatus)
#### [GlobalMemoryStatusEx](/windows/desktop/api/WinBase/)
#### [GlobalReAlloc](/windows/desktop/api/WinBase/nf-winbase-globalrealloc)
#### [GlobalSize](/windows/desktop/api/WinBase/nf-winbase-globalsize)
#### [GlobalUnlock](/windows/desktop/api/WinBase/nf-winbase-globalunlock)
#### [HeapAlloc](/windows/desktop/api/HeapApi/nf-heapapi-heapalloc)
#### [HeapCompact](/windows/desktop/api/HeapApi/nf-heapapi-heapcompact)
#### [HeapCreate](/windows/desktop/api/HeapApi/nf-heapapi-heapcreate)
#### [HeapDestroy](/windows/desktop/api/HeapApi/nf-heapapi-heapdestroy)
#### [HeapFree](/windows/desktop/api/HeapApi/nf-heapapi-heapfree)
#### [HeapLock](/windows/desktop/api/HeapApi/nf-heapapi-heaplock)
#### [HeapQueryInformation](/windows/desktop/api/HeapApi/nf-heapapi-heapqueryinformation)
#### [HeapReAlloc](/windows/desktop/api/HeapApi/nf-heapapi-heaprealloc)
#### [HeapSetInformation](/windows/desktop/api/HeapApi/nf-heapapi-heapsetinformation)
#### [HeapSize](/windows/desktop/api/HeapApi/nf-heapapi-heapsize)
#### [HeapUnlock](/windows/desktop/api/HeapApi/nf-heapapi-heapunlock)
#### [HeapValidate](/windows/desktop/api/HeapApi/nf-heapapi-heapvalidate)
#### [HeapWalk](/windows/desktop/api/HeapApi/nf-heapapi-heapwalk)
#### [IsBadCodePtr](/windows/desktop/api/WinBase/nf-winbase-isbadcodeptr)
#### [IsBadReadPtr](/windows/desktop/api/WinBase/nf-winbase-isbadreadptr)
#### [IsBadStringPtr](/windows/desktop/api/WinBase/nf-winbase-isbadstringptra)
#### [IsBadWritePtr](/windows/desktop/api/WinBase/nf-winbase-isbadwriteptr)
#### [LocalAlloc](/windows/desktop/api/WinBase/nf-winbase-localalloc)
#### [LocalDiscard](https://msdn.microsoft.com/en-us/library/Aa366727(v=VS.85).aspx)
#### [LocalFlags](/windows/desktop/api/WinBase/nf-winbase-localflags)
#### [LocalFree](/windows/desktop/api/WinBase/nf-winbase-localfree)
#### [LocalHandle](/windows/desktop/api/WinBase/nf-winbase-localhandle)
#### [LocalLock](/windows/desktop/api/WinBase/nf-winbase-locallock)
#### [LocalReAlloc](/windows/desktop/api/WinBase/nf-winbase-localrealloc)
#### [LocalSize](/windows/desktop/api/WinBase/nf-winbase-localsize)
#### [LocalUnlock](/windows/desktop/api/WinBase/nf-winbase-localunlock)
#### [MapViewOfFile](https://msdn.microsoft.com/en-us/library/Aa366761(v=VS.85).aspx)
#### [MapViewOfFile2](https://msdn.microsoft.com/en-us/library/Mt492557(v=VS.85).aspx)
#### [MapViewOfFileEx](https://msdn.microsoft.com/en-us/library/Aa366763(v=VS.85).aspx)
#### [MapViewOfFileExNuma](/windows/desktop/api/WinBase/nf-winbase-mapviewoffileexnuma)
#### [MapViewOfFileFromApp](/windows/desktop/api/MemoryApi/nf-memoryapi-mapviewoffilefromapp)
#### [MapViewOfFileNuma2](https://msdn.microsoft.com/en-us/library/Mt492558(v=VS.85).aspx)
#### [MapUserPhysicalPages](https://msdn.microsoft.com/en-us/library/Aa366753(v=VS.85).aspx)
#### [MapUserPhysicalPagesScatter](/windows/desktop/api/WinBase/nf-winbase-mapuserphysicalpagesscatter)
#### [MoveMemory](/windows/desktop/api/WinBase/nf-srbhelper-srbmovememory)
#### [OpenFileMapping](/windows/desktop/api/WinBase/nf-winbase-openfilemappinga)
#### [OpenFileMappingFromApp](/windows/desktop/api/MemoryApi/nf-memoryapi-openfilemappingfromapp)
#### [OfferVirtualMemory](https://msdn.microsoft.com/en-us/library/Dn781436(v=VS.85).aspx)
#### [PrefetchVirtualMemory](https://msdn.microsoft.com/en-us/library/Hh780543(v=VS.85).aspx)
#### [QueryMemoryResourceNotification](https://msdn.microsoft.com/en-us/library/Aa366799(v=VS.85).aspx)
#### [QueryVirtualMemoryInformation](/windows/desktop/api/MemoryApi/nf-memoryapi-queryvirtualmemoryinformation)
#### [ReclaimVirtualMemory](https://msdn.microsoft.com/en-us/library/Dn781437(v=VS.85).aspx)
#### [RegisterBadMemoryNotification](https://msdn.microsoft.com/en-us/library/Hh691013(v=VS.85).aspx)
#### [RemoveSecureMemoryCacheCallback](/windows/desktop/api/WinBase/nf-winbase-removesecurememorycachecallback)
#### [ResetWriteWatch](https://msdn.microsoft.com/en-us/library/Aa366874(v=VS.85).aspx)
#### [SecureMemoryCacheCallback](/windows/desktop/api/WinNT/nc-winnt-psecure_memory_cache_callback)
#### [SecureZeroMemory](/windows/desktop/api/WinBase/)
#### [SetProcessDEPPolicy](/windows/desktop/api/WinBase/nf-winbase-setprocessdeppolicy)
#### [SetProcessValidCallTargets](https://msdn.microsoft.com/en-us/library/Dn934202(v=VS.85).aspx)
#### [SetSystemFileCacheSize](https://msdn.microsoft.com/en-us/library/Aa965240(v=VS.85).aspx)
#### [UnmapViewOfFile](https://msdn.microsoft.com/en-us/library/Aa366882(v=VS.85).aspx)
#### [UnmapViewOfFile2](https://msdn.microsoft.com/en-us/library/Mt492559(v=VS.85).aspx)
#### [UnmapViewOfFileEx](https://msdn.microsoft.com/en-us/library/Mt670639(v=VS.85).aspx)
#### [UnregisterBadMemoryNotification](https://msdn.microsoft.com/en-us/library/Hh691014(v=VS.85).aspx)
#### [VirtualAlloc](https://msdn.microsoft.com/en-us/library/Aa366887(v=VS.85).aspx)
#### [VirtualAllocEx](https://msdn.microsoft.com/en-us/library/Aa366890(v=VS.85).aspx)
#### [VirtualAllocExNuma](https://msdn.microsoft.com/en-us/library/Aa366891(v=VS.85).aspx)
#### [VirtualAllocFromApp](/windows/desktop/api/MemoryApi/nf-memoryapi-virtualallocfromapp)
#### [VirtualFree](https://msdn.microsoft.com/en-us/library/Aa366892(v=VS.85).aspx)
#### [VirtualFreeEx](https://msdn.microsoft.com/en-us/library/Aa366894(v=VS.85).aspx)
#### [VirtualLock](https://msdn.microsoft.com/en-us/library/Aa366895(v=VS.85).aspx)
#### [VirtualProtect](https://msdn.microsoft.com/en-us/library/Aa366898(v=VS.85).aspx)
#### [VirtualProtectEx](https://msdn.microsoft.com/en-us/library/Aa366899(v=VS.85).aspx)
#### [VirtualProtectFromApp](/windows/desktop/api/MemoryApi/nf-memoryapi-virtualprotectfromapp)
#### [VirtualQuery](https://msdn.microsoft.com/en-us/library/Aa366902(v=VS.85).aspx)
#### [VirtualQueryEx](https://msdn.microsoft.com/en-us/library/Aa366907(v=VS.85).aspx)
#### [VirtualUnlock](https://msdn.microsoft.com/en-us/library/Aa366910(v=VS.85).aspx)
#### [ZeroMemory](/windows/desktop/api/WinBase/nf-minitape-rtlzeromemory)
#### [AtlThunk_AllocateData](/windows/desktop/api/atlthunk/nf-atlthunk-atlthunk_allocatedata)
#### [AtlThunk_InitData](/windows/desktop/api/atlthunk/nf-atlthunk-atlthunk_initdata)
#### [AtlThunk_DataToCode](/windows/desktop/api/atlthunk/nf-atlthunk-atlthunk_datatocode)
#### [AtlThunk_FreeData](/windows/desktop/api/atlthunk/nf-atlthunk-atlthunk_freedata)
### [Memory Management Registry Keys](memory-management-registry-keys.md)
### [Memory Management Structures](memory-management-structures.md)
#### [CFG_CALL_TARGET_INFO](-cfg-call-target-info.md)
#### [HEAP_OPTIMIZE_RESOURCES_INFORMATION ](https://msdn.microsoft.com/en-us/library/Dn872745(v=VS.85).aspx)
#### [MEMORY_BASIC_INFORMATION](/windows/desktop/api/Winnt/ns-winnt-_memory_basic_information)
#### [MEMORYSTATUS](/windows/desktop/api/WinBase/ns-winbase-_memorystatus)
#### [MEMORYSTATUSEX](/windows/desktop/api/WinBase/)
#### [PROCESS_HEAP_ENTRY](https://msdn.microsoft.com/en-us/library/Aa366798(v=VS.85).aspx)
#### [WIN32_MEMORY_RANGE_ENTRY](https://msdn.microsoft.com/en-us/library/Hh780544(v=VS.85).aspx)
#### [WIN32_MEMORY_REGION_INFORMATION](/windows/desktop/api/MemoryApi/ns-memoryapi-win32_memory_region_information)
#### [AtlThunkData_t](/windows/desktop/api/atlthunk/)
### [Memory Protection Constants](memory-protection-constants.md)
### [Memory Management Tracing Events](memory-management-tracing-events.md)
#### [ETW_HEAP_EVENT_ALLOC](etw-heap-event-alloc.md)
#### [ETW_HEAP_EVENT_FREE](etw-heap-event-free.md)
#### [ETW_HEAP_EVENT_REALLOC](etw-heap-event-realloc.md)
# [Trusted Execution](trusted-execution.md)
## [Trusted Execution Reference](trusted-execution-reference.md)
### [Trusted Execution Enumerations](trusted-execution-enumerations.md)
#### [ENCLAVE_SEALING_IDENTITY_POLICY](/windows/desktop/api/ntenclv/ne-ntenclv-enclave_sealing_identity_policy)
### [Trusted Execution Functions](trusted-execution-functions.md)
#### [CallEnclave](/windows/desktop/api/Enclaveapi/nf-enclaveapi-callenclave)
#### [CreateEnclave](/windows/desktop/api/enclaveapi/nf-enclaveapi-createenclave)
#### [DeleteEnclave](/windows/desktop/api/Enclaveapi/nf-enclaveapi-deleteenclave)
#### [EnclaveGetAttestationReport](/windows/desktop/api/winenclaveapi/nf-winenclaveapi-enclavegetattestationreport)
#### [EnclaveGetEnclaveInformation](/windows/desktop/api/winenclaveapi/nf-winenclaveapi-enclavegetenclaveinformation)
#### [EnclaveSealData](/windows/desktop/api/winenclaveapi/nf-winenclaveapi-enclavesealdata)
#### [EnclaveUnsealData](/windows/desktop/api/winenclaveapi/nf-winenclaveapi-enclaveunsealdata)
#### [EnclaveVerifyAttestationReport](/windows/desktop/api/winenclaveapi/nf-winenclaveapi-enclaveverifyattestationreport)
#### [InitializeEnclave](/windows/desktop/api/enclaveapi/nf-enclaveapi-initializeenclave)
#### [IsEnclaveTypeSupported](/windows/desktop/api/enclaveapi/nf-enclaveapi-isenclavetypesupported)
#### [LoadEnclaveData](/windows/desktop/api/enclaveapi/nf-enclaveapi-loadenclavedata)
#### [LoadEnclaveImage](/windows/desktop/api/Enclaveapi/nf-enclaveapi-loadenclaveimagew)
#### [TerminateEnclave](/windows/desktop/api/Enclaveapi/nf-enclaveapi-terminateenclave)
### [Trusted Execution Structures](trusted-execution-structures.md)
#### [ENCLAVE_CREATE_INFO_SGX](/windows/desktop/api/winnt/ns-winnt-_enclave_create_info_sgx)
#### [ENCLAVE_CREATE_INFO_VBS](/windows/desktop/api/winnt/ns-winnt-_enclave_create_info_vbs)
#### [ENCLAVE_IDENTITY](/windows/desktop/api/ntenclv/ns-ntenclv-enclave_identity)
#### [ENCLAVE_INFORMATION](/windows/desktop/api/ntenclv/ns-ntenclv-enclave_information)
#### [ENCLAVE_INIT_INFO_SGX](/windows/desktop/api/winnt/ns-winnt-_enclave_init_info_sgx)
#### [ENCLAVE_INIT_INFO_VBS](/windows/desktop/api/winnt/ns-winnt-_enclave_init_info_vbs)
#### [IMAGE_ENCLAVE_CONFIG32](/windows/desktop/api/winnt/ns-winnt-_image_enclave_config32)
#### [IMAGE_ENCLAVE_CONFIG64](/windows/desktop/api/winnt/)
#### [IMAGE_ENCLAVE_IMPORT](/windows/desktop/api/winnt/ns-winnt-_image_enclave_import)
#### [VBS_ENCLAVE_REPORT](/windows/desktop/api/ntenclv/ns-ntenclv-vbs_enclave_report)
#### [VBS_ENCLAVE_REPORT_MODULE](/windows/desktop/api/ntenclv/ns-ntenclv-vbs_enclave_report_module)
#### [VBS_ENCLAVE_REPORT_PKG_HEADER](/windows/desktop/api/ntenclv/ns-ntenclv-vbs_enclave_report_pkg_header)
#### [VBS_ENCLAVE_REPORT_VARDATA_HEADER](/windows/desktop/api/ntenclv/ns-ntenclv-vbs_enclave_report_vardata_header)
