
Repro for [AvaloniaUI Bug 14933](https://github.com/AvaloniaUI/Avalonia/issues/14933)
Shows, that an avaloniaui project created with "file-new" experience outputs an iOS app, that simply crashes on startup:

```

Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Private.CoreLib.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Runtime.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Threading.Thread.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/Avalonia.Fonts.Inter.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/Avalonia.ReactiveUI.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/AvaloniaiOSCrash03.iOS.dll
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/AvaloniaiOSCrash03.dll
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Numerics.Vectors.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Runtime.Loader.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Reflection.Emit.ILGeneration.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Reflection.Emit.Lightweight.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Reflection.Primitives.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Diagnostics.Tracing.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Runtime.Intrinsics.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/Microsoft.Win32.Primitives.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Text.Encoding.Extensions.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Threading.ThreadPool.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Resources.Writer.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Xml.XDocument.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Reflection.Emit.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Runtime.CompilerServices.Unsafe.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Runtime.InteropServices.RuntimeInformation.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Security.Cryptography.Algorithms.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Xml.ReaderWriter.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Security.Cryptography.Primitives.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Linq.Queryable.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Resources.ResourceManager.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Runtime.Extensions.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Diagnostics.Debug.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Threading.Tasks.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.IO.FileSystem.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Xml.XPath.XDocument.dll [External]
Loaded assembly: /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/System.Diagnostics.StackTrace.dll [External]
Thread started:  #2
Thread started: .NET Timer #3
[0:] LogHost: Initializing to normal mode (.cctor)

=================================================================
	Native Crash Reporting
=================================================================
Got a SIGBUS while executing native code. This usually indicates
a fatal error in the mono runtime or one of the native libraries 
used by your application.
=================================================================

=================================================================
	Native stacktrace:
=================================================================
	0x1271b40a0 - /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/libmonosgen-2.0.dylib : mono_dump_native_crash_info
	0x12716428c - /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/libmonosgen-2.0.dylib : mono_handle_native_crash
	0x1270cb798 - /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/libmonosgen-2.0.dylib : mono_sigsegv_signal_handler_debug
	0x124ae37e0 - /usr/lib/system/libsystem_platform.dylib : _sigtramp
	0x1b8650ff8 - /Library/Developer/CoreSimulator/Volumes/iOS_21E213/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS 17.4.simruntime/Contents/Resources/RuntimeRoot/System/Library/Fr
ameworks/OpenGLES.framework/libCoreVMClient.dylib : cvmsServerElementBuild
	0x1b864ce34 - /Library/Developer/CoreSimulator/Volumes/iOS_21E213/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS 17.4.simruntime/Contents/Resources/RuntimeRoot/System/Library/Frameworks/OpenGLES.framework/libCoreVMClient.dylib : cvms_element_build_from_source
	0x1b8643854 - /Library/Developer/CoreSimulator/Volumes/iOS_21E213/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS 17.4.simruntime/Contents/Resources/RuntimeRoot/System/Library/Frameworks/OpenGLES.framework/libCVMSPluginSupport.dylib : _Z26cvm_deferred_build_modularPv
	0x180171978 - /Library/Developer/CoreSimulator/Volumes/iOS_21E213/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS 17.4.simruntime/Contents/Resources/RuntimeRoot/usr/lib/system/libdispatch.dylib : _dispatch_client_callout
	0x180179b10 - /Library/Developer/CoreSimulator/Volumes/iOS_21E213/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS 17.4.simruntime/Contents/Resources/RuntimeRoot/usr/lib/sy
stem/libdispatch.dylib : _dispatch_lane_serial_drain
	0x18017a688 - /Library/Developer/CoreSimulator/Volumes/iOS_21E213/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS 17.4.simruntime/Contents/Resources/RuntimeRoot/usr/lib/system/libdispatch.dylib : _dispatch_lane_invoke
	0x180185a84 - /Library/Developer/CoreSimulator/Volumes/iOS_21E213/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS 17.4.simruntime/Contents/Resources/RuntimeRoot/usr/lib/system/libdispatch.dylib : _dispatch_root_queue_drain_deferred_wlh
	0x1801850d0 - /Library/Developer/CoreSimulator/Volumes/iOS_21E213/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS 17.4.simruntime/Contents/Resources/RuntimeRoot/usr/lib/system/libdispatch.dylib : _dispatch_workloop_worker_thread
	0x124b57814 - /usr/lib/system/libsystem_pthread.dylib : _pthread_wqthread
	0x124b565d4 - /usr/lib/system/libsystem_pthread.dylib : start_wqthread

=================================================================
	Basic Fault Address Reporting
======================
===========================================
Memory around native instruction pointer (0x124ae3410):0x124ae3400  28 24 40 a8 2a 2c 41 a8 21 80 00 91 42 00 05 cb  ($@.*,A.!...B...
0x124ae3410  0c 34 00 a9 0e 3c 01 a9 42 00 01 f1 29 01 00 54  .4...<..B...)..T
0x124ae3420  68 24 00 a9 6a 2c 01 a9 63 80 00 91 28 24 40 a8  h$..j
,..c...($@.
0x124ae3430  2a 2c 41 a8 21 80 00 91 42 80 00 f1 28 ff ff 54  *,A.!...B...(..T

=================================================================
	Native Crash Reporting
=================================================================
Got a SIGBUS while executing native code. This usually indicates
a fatal error in the mono runtime or one of the native libraries 
used by your application.
=================================================================

An error has occurred in the native fault reporting. Some diagnostic information will be unavailable.

=================================================================
	Native stacktrace:
=================================================================
	0x1271b40a0 - /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/libmonosgen-2.0.dylib : mono_dump_native_crash_info
	0x12716428c - /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/libmonosgen-2.0.dylib : mono_handle_native_crash
	0x1270cb798 - /Users/admin/Library/Developer/CoreSimulator/Devices/8340112E-F1CF-4793-82AB-C015D4F70148/data/Containers/Bundle/Application/DE6F2B96-16F1-4BD8-99EB-09BECD4D51CF/AvaloniaiOSCrash03.iOS.app/libmonosgen-2.0.dylib : mono_sigsegv_signal_handler_debug
	0x124ae37e0 - /usr/lib/system/libsystem_platform.dylib : _sigtramp
	0x1b8650ff8 - /Library/Developer/CoreSimulator/Volumes/iOS_21E213/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS 17.4.simruntime/Contents/Resources/RuntimeRoot/System/Library/Frameworks/OpenGLES.framework/libCoreVMClient.dylib : cvmsServerElementBuild
	0x1b864ce34 - /Library/Developer/CoreSimulator/Volumes/iOS_21E213/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS 17.4.simruntime/Contents/Resources/RuntimeRoot/System/Library/Frameworks/OpenGLES.framework/libCoreVMClient.dylib : cvms_element_build_from_source
	0x1b8643854 - /Library/Developer/CoreSimulator/Volumes/iOS_21E213/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS 17.4.simruntime/Contents/Resources/RuntimeRoot/System/Library/Frameworks/OpenGLES.framework/libCVMSPluginSupport.dylib : _Z26cvm_deferred_build_modularPv
	0x180171978 - /Library/Developer/CoreSimulator/Volumes/iOS_21E213/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS 17.4.simruntime/Contents/Resources/RuntimeRoot/usr/lib/system/libdispatch.dylib : _dispatch_client_callout
	0x180179b10 - /Library/Developer/CoreSimulator/Volumes/iOS_21E213/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS 17.4.simruntime/Contents/Resources/RuntimeRoot/usr/lib/system/libdispatch.dylib : _dispatch_lane_serial_drain
	0x18017a688 - /Library/Developer/CoreSimulator/Volumes/iOS_21E213/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS 17.4.simruntime/Contents/Resources/RuntimeRoot/usr/lib/system/libdispatch.dylib : _dispatch_lane_invoke
	0x180185a84 - /Library/Developer/CoreSimulator/Volumes/iOS_21E21
3/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS 17.4.simruntime/Contents/Resources/RuntimeRoot/usr/lib/system/libdispatch.dylib : _dispatch_root_queue_drain_deferred_wlh
	0x1801850d0 - /Library/Developer/CoreSimulator/Volumes/iOS_21E213/Library/Developer/CoreSimulator/Profiles/Runtimes/iOS 17.4.simruntime/Contents/Resources/RuntimeRoot/usr/lib/system/libdispatch.dylib : _dispatch_workloop_worker_thread
	0x124b57814 - /usr/lib/system/libsystem_pthread.dylib : _pthread_wqthread
	0x124b565d4 - /usr/lib/system/libsystem_pthread.dylib : start_wqthread

Exiting early due to double fault.


```