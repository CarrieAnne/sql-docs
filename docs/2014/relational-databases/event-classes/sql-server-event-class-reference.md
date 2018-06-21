---
title: "SQL Server Event Class Reference | Microsoft Docs"
ms.custom: ""
ms.date: "07/24/2017"
ms.prod: "sql-server-2014"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "database-engine"
ms.tgt_pltfrm: ""
ms.topic: "article"
topic_type: 
  - "apiref"
helpviewer_keywords: 
  - "events [SQL Server], event classes"
  - "event classes [SQL Server], listed"
  - "event classes [SQL Server]"
  - "SQL Server event classes, listed"
  - "SQL Server event classes"
ms.assetid: 0f0fe567-e115-4ace-b63c-73dc3428c0f6
caps.latest.revision: 33
author: "JennieHubbard"
ms.author: "jhubbard"
manager: "jhubbard"
---
# SQL Server Event Class Reference
  [!INCLUDE[ssSqlProfiler](../../includes/sssqlprofiler-md.md)] lets you record events as they occur in an instance of the [!INCLUDE[msCoName](../../includes/msconame-md.md)] [!INCLUDE[ssDEnoversion](../../includes/ssdenoversion-md.md)]. The recorded events are instances of the event classes in the trace definition. In [!INCLUDE[ssSqlProfiler](../../includes/sssqlprofiler-md.md)], event classes and their event categories are available on the **Events Selection** tab of the **Trace File Properties** dialog box.  
  
 The following table describes the event categories and lists their associated event classes.  
  
|Event Category|Event Classes|  
|--------------------|-------------------|  
|The [Broker Event Category](broker-event-category.md) includes event classes that are produced by the [!INCLUDE[ssSB](../../includes/sssb-md.md)].|[Broker:Activation Event Class](broker-activation-event-class.md)<br /><br /> [Broker:Connection Event Class](broker-connection-event-class.md)<br /><br /> [Broker:Conversation Event Class](broker-conversation-event-class.md)<br /><br /> [Broker:Conversation Group Event Class](broker-conversation-group-event-class.md)<br /><br /> [Broker:Corrupted Message Event Class](broker-corrupted-message-event-class.md)<br /><br /> [Broker:Forwarded Message Dropped Event Class](broker-forwarded-message-dropped-event-class.md)<br /><br /> [Broker:Forwarded Message Sent Event Class](broker-forwarded-message-sent-event-class.md)<br /><br /> [Broker:Message Classify Event Class](broker-message-classify-event-class.md)<br /><br /> [Broker:Message Drop Event Class](broker-message-drop-event-class.md)<br /><br /> [Broker:Remote Message Ack Event Class](broker-remote-message-ack-event-class.md)|  
|The [Cursors Event Category](cursors-event-category.md) includes event classes that are produced by cursor operations.|[CursorClose Event Class](cursorclose-event-class.md)<br /><br /> [CursorExecute Event Class](cursorexecute-event-class.md)<br /><br /> [CursorImplicitConversion Event Class](cursorimplicitconversion-event-class.md)<br /><br /> [CursorOpen Event Class](cursoropen-event-class.md)<br /><br /> [CursorPrepare Event Class](cursorprepare-event-class.md)<br /><br /> [CursorRecompile Event Class](cursorrecompile-event-class.md)<br /><br /> [CursorUnprepare Event Class](cursorunprepare-event-class.md)|  
|The [CLR Event Category](clr-event-category.md) includes event classes that are produced by the execution of .NET common language runtime (CLR) objects.|[Assembly Load Event Class](../../database-engine/assembly-load-event-class.md)|  
|The [Database Event Category](database-event-category.md) includes event classes that are produced when data or log files grow or shrink automatically.|[Data File Auto Grow Event Class](data-file-auto-grow-event-class.md)<br /><br /> [Data File Auto Shrink Event Class](data-file-auto-shrink-event-class.md)<br /><br /> [Database Mirroring State Change Event Class](database-mirroring-state-change-event-class.md)<br /><br /> [Log File Auto Grow Event Class](log-file-auto-grow-event-class.md)<br /><br /> [Log File Auto Shrink Event Class](log-file-auto-shrink-event-class.md)|  
|The [Deprecation Event Category](deprecation-event-category.md) includes deprecation related events.|[Deprecation Announcement Event Class](deprecation-announcement-event-class.md)<br /><br /> [Deprecation Final Support Event Class](deprecation-final-support-event-class.md)|  
|The [Errors and Warnings Event Category &#40;Database Engine&#41;](errors-and-warnings-event-category-database-engine.md) includes event classes that are produced when a [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)].|[Attention Event Class](attention-event-class.md)<br /><br /> [Background Job Error Event Class](background-job-error-event-class.md)<br /><br /> [Blocked Process Report Event Class](blocked-process-report-event-class.md)<br /><br /> [CPU Threshold Exceeded Event Class](cpu-threshold-exceeded-event-class.md)<br /><br /> [ErrorLog Event Class](errorlog-event-class.md)<br /><br /> [EventLog Event Class](eventlog-event-class.md)<br /><br /> [Exception Event Class](exception-event-class.md)<br /><br /> [Exchange Spill Event Class](exchange-spill-event-class.md)<br /><br /> [Execution Warnings Event Class](execution-warnings-event-class.md)<br /><br /> [Hash Warning Event Class](hash-warning-event-class.md)<br /><br /> [Missing Column Statistics Event Class](missing-column-statistics-event-class.md)<br /><br /> [Missing Join Predicate Event Class](missing-join-predicate-event-class.md)<br /><br /> [Sort Warnings Event Class](sort-warnings-event-class.md)<br /><br /> [User Error Message Event Class](user-error-message-event-class.md)|  
|The [Full Text Event Category](full-text-event-category.md) includes event classes that are produced when full-text searches are started, interrupted, or stopped.|[FT:Crawl Aborted Event Class](ft-crawl-aborted-event-class.md)<br /><br /> [FT:Crawl Started Event Class](ft-crawl-started-event-class.md)<br /><br /> [FT:Crawl Stopped Event Class](ft-crawl-stopped-event-class.md)|  
|The [Locks Event Category](locks-event-category.md) includes event classes that are produced when a lock is acquired, cancelled, released, or has some other action performed on it.|[Deadlock Graph Event Class](deadlock-graph-event-class.md)<br /><br /> [Lock:Acquired Event Class](lock-acquired-event-class.md)<br /><br /> [Lock:Cancel Event Class](lock-cancel-event-class.md)<br /><br /> [Lock:Deadlock Chain Event Class](lock-deadlock-chain-event-class.md)<br /><br /> [Lock:Deadlock Event Class](lock-deadlock-event-class.md)<br /><br /> [Lock:Escalation Event Class](lock-escalation-event-class.md)<br /><br /> [Lock:Released Event Class](lock-released-event-class.md)<br /><br /> [Lock:Timeout &#40;timeout &#62; 0&#41; Event Class](lock-timeout-timeout-0-event-class.md)<br /><br /> [Lock:Timeout Event Class](lock-timeout-event-class.md)|  
|The [Objects Event Category](objects-event-category.md) includes event classes that are produced when database objects are created, opened, closed, dropped, or deleted.|[Auto Stats Event Class](auto-stats-event-class.md)<br /><br /> [Object:Altered Event Class](object-altered-event-class.md)<br /><br /> [Object:Created Event Class](object-created-event-class.md)<br /><br /> [Object:Deleted Event Class](object-deleted-event-class.md)|  
|The [OLEDB Event Category](oledb-event-category.md) includes event classes that are produced by OLE DB calls.|[OLEDB Call Event Class](oledb-call-event-class.md)<br /><br /> [OLEDB DataRead Event Class](oledb-dataread-event-class.md)<br /><br /> [OLEDB Errors Event Class](oledb-errors-event-class.md)<br /><br /> [OLEDB Provider Information Event Class](oledb-provider-information-event-class.md)<br /><br /> [OLEDB QueryInterface Event Class](oledb-queryinterface-event-class.md)|  
|The [Performance Event Category](performance-event-category.md) includes event classes that are produced when SQL data manipulation language (DML) operators execute.|[Degree of Parallelism &#40;7.0 Insert&#41; Event Class](degree-of-parallelism-7-0-insert-event-class.md)<br /><br /> [Performance Statistics Event Class](performance-statistics-event-class.md)<br /><br /> [Showplan All Event Class](showplan-all-event-class.md)<br /><br /> [Showplan All for Query Compile Event Class](showplan-all-for-query-compile-event-class.md)<br /><br /> [Showplan Statistics Profile Event Class](showplan-statistics-profile-event-class.md)<br /><br /> [Showplan Text Event Class](showplan-text-event-class.md)<br /><br /> [Showplan Text &#40;Unencoded&#41; Event Class](showplan-text-unencoded-event-class.md)<br /><br /> [Showplan XML Event Class](showplan-xml-event-class.md)<br /><br /> [Showplan XML for Query Compile Event Class](showplan-xml-for-query-compile-event-class.md)<br /><br /> [Showplan XML Statistics Profile Event Class](showplan-xml-statistics-profile-event-class.md)<br /><br /> [SQL:FullTextQuery Event Class](sql-fulltextquery-event-class.md)|  
|The [Progress Report Event Category](progress-report-event-category.md) includes the **Progress Report: Online Index Operation** event class.|[Progress Report: Online Index Operation Event Class](progress-report-online-index-operation-event-class.md)|  
|The [Scans Event Category](scans-event-category.md) includes event classes that are produced when tables and indexes are scanned.|[Scan:Started Event Class](scan-started-event-class.md)<br /><br /> [Scan:Stopped Event Class](scan-stopped-event-class.md)|  
|The [Security Audit Event Category](security-audit-event-category-sql-server-profiler.md) includes event classes that are used to audit server activity.|[Audit Add DB User Event Class](audit-add-db-user-event-class.md)<br /><br /> [Audit Add Login to Server Role Event Class](audit-add-login-to-server-role-event-class.md)<br /><br /> [Audit Add Member to DB Role Event Class](audit-add-member-to-db-role-event-class.md)<br /><br /> [Audit Add Role Event Class](audit-add-role-event-class.md)<br /><br /> [Audit Addlogin Event Class](audit-addlogin-event-class.md)<br /><br /> [Audit App Role Change Password Event Class](audit-app-role-change-password-event-class.md)<br /><br /> [Audit Backup and Restore Event Class](audit-backup-and-restore-event-class.md)<br /><br /> [Audit Broker Conversation Event Class](audit-broker-conversation-event-class.md)<br /><br /> [Audit Broker Login Event Class](audit-broker-login-event-class.md)<br /><br /> [Audit Change Audit Event Class](audit-change-audit-event-class.md)<br /><br /> [Audit Change Database Owner Event Class](audit-change-database-owner-event-class.md)<br /><br /> [Audit Database Management Event Class](audit-database-management-event-class.md)<br /><br /> [Audit Database Object Access Event Class](audit-database-object-access-event-class.md)<br /><br /> [Audit Database Object GDR Event Class](audit-database-object-gdr-event-class.md)<br /><br /> [Audit Database Object Management Event Class](audit-database-object-management-event-class.md)<br /><br /> [Audit Database Object Take Ownership Event Class](audit-database-object-take-ownership-event-class.md)<br /><br /> [Audit Database Operation Event Class](audit-database-operation-event-class.md)<br /><br /> [Audit Database Principal Impersonation Event Class](audit-database-principal-impersonation-event-class.md)<br /><br /> [Audit Database Principal Management Event Class](audit-database-principal-management-event-class.md)<br /><br /> [Audit Database Scope GDR Event Class](audit-database-scope-gdr-event-class.md)<br /><br /> [Audit DBCC Event Class](audit-dbcc-event-class.md)<br /><br /> [Audit Login Change Password Event Class](audit-login-change-password-event-class.md)<br /><br /> [Audit Login Change Property Event Class](audit-login-change-property-event-class.md)<br /><br /> [Audit Login Event Class](audit-login-event-class.md)<br /><br /> [Audit Login Failed Event Class](audit-login-failed-event-class.md)<br /><br /> [Audit Login GDR Event Class](audit-login-gdr-event-class.md)<br /><br /> [Audit Logout Event Class](audit-logout-event-class.md)<br /><br /> [Audit Object Derived Permission Event Class](audit-object-derived-permission-event-class.md)<br /><br /> [Audit Schema Object Access Event Class](audit-schema-object-access-event-class.md)<br /><br /> [Audit Schema Object GDR Event Class](audit-schema-object-gdr-event-class.md)<br /><br /> [Audit Schema Object Management Event Class](audit-schema-object-management-event-class.md)<br /><br /> [Audit Schema Object Take Ownership Event Class](audit-schema-object-take-ownership-event-class.md)<br /><br /> [Audit Server Alter Trace Event Class](audit-server-alter-trace-event-class.md)<br /><br /> [Audit Server Object GDR Event Class](audit-server-object-gdr-event-class.md)<br /><br /> [Audit Server Object Management Event Class](audit-server-object-management-event-class.md)<br /><br /> [Audit Server Object Take Ownership Event Class](audit-server-object-take-ownership-event-class.md)<br /><br /> [Audit Server Operation Event Class](audit-server-operation-event-class.md)<br /><br /> [Audit Server Principal Impersonation Event Class](audit-server-principal-impersonation-event-class.md)<br /><br /> [Audit Server Principal Management Event Class](audit-server-principal-management-event-class.md)<br /><br /> [Audit Server Scope GDR Event Class](audit-server-scope-gdr-event-class.md)<br /><br /> [Audit Server Starts and Stops Event Class](audit-server-starts-and-stops-event-class.md)<br /><br /> [Audit Statement Permission Event Class](audit-statement-permission-event-class.md)|  
|The [Server Event Category](server-event-category.md) contains general server events.|[Mount Tape Event Class](mount-tape-event-class.md)<br /><br /> [Server Memory Change Event Class](server-memory-change-event-class.md)<br /><br /> [Trace File Close Event Class](trace-file-close-event-class.md)|  
|The [Sessions Event Category](sessions-event-category.md) includes event classes produced by clients connecting to and disconnecting from an instance of [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)].|[ExistingConnection Event Class](existingconnection-event-class.md)|  
|The [Stored Procedures Event Category](stored-procedures-event-category.md) includes event classes produced by the execution of stored procedures.|[PreConnect:Completed Event Class](preconnect-completed-event-class.md)<br /><br /> [PreConnect:Starting Event Class](preconnect-starting-event-class.md)<br /><br /> [RPC:Completed Event Class](rpc-completed-event-class.md)<br /><br /> [RPC Output Parameter Event Class](rpc-output-parameter-event-class.md)<br /><br /> [RPC:Starting Event Class](rpc-starting-event-class.md)<br /><br /> [SP:CacheHit Event Class](sp-cachehit-event-class.md)<br /><br /> [SP:CacheInsert Event Class](sp-cacheinsert-event-class.md)<br /><br /> [SP:CacheMiss Event Class](sp-cachemiss-event-class.md)<br /><br /> [SP:CacheRemove Event Class](sp-cacheremove-event-class.md)<br /><br /> [SP:Completed Event Class](sp-completed-event-class.md)<br /><br /> [SP:Recompile Event Class](sp-recompile-event-class.md)<br /><br /> [SP:Starting Event Class](sp-starting-event-class.md)<br /><br /> [SP:StmtCompleted Event Class](sp-stmtcompleted-event-class.md)<br /><br /> [SP:StmtStarting Event Class](sp-stmtstarting-event-class.md)|  
|The [Transactions Event Category](transactions-event-category.md) includes event classes produced by the execution of [!INCLUDE[msCoName](../../includes/msconame-md.md)] Distributed Transaction Coordinator transactions or by writing to the transaction log.|[DTCTransaction Event Class](dtctransaction-event-class.md)<br /><br /> [SQLTransaction Event Class](sqltransaction-event-class.md)<br /><br /> [TM: Begin Tran Completed Event Class](tm-begin-tran-completed-event-class.md)<br /><br /> [TM: Begin Tran Starting Event Class](tm-begin-tran-starting-event-class.md)<br /><br /> [TM: Commit Tran Completed Event Class](tm-commit-tran-completed-event-class.md)<br /><br /> [TM: Commit Tran Starting Event Class](tm-commit-tran-starting-event-class.md)<br /><br /> [TM: Promote Tran Completed Event Class](tm-promote-tran-completed-event-class.md)<br /><br /> [TM: Promote Tran Starting Event Class](tm-promote-tran-starting-event-class.md)<br /><br /> [TM: Rollback Tran Completed Event Class](tm-rollback-tran-completed-event-class.md)<br /><br /> [TM: Rollback Tran Starting Event Class](tm-rollback-tran-starting-event-class.md)<br /><br /> [TM: Save Tran Completed Event Class](tm-save-tran-completed-event-class.md)<br /><br /> [TM: Save Tran Starting Event Class](tm-save-tran-starting-event-class.md)<br /><br /> [TransactionLog Event Class](transactionlog-event-class.md)|  
|The [TSQL Event Category](tsql-event-category.md) includes event classes produced by the execution of Transact-SQL statements passed to an instance of [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] from the client.|[Exec Prepared SQL Event Class](exec-prepared-sql-event-class.md)<br /><br /> [Prepare SQL Event Class](prepare-sql-event-class.md)<br /><br /> [SQL:BatchCompleted Event Class](sql-batchcompleted-event-class.md)<br /><br /> [SQL:BatchStarting Event Class](sql-batchstarting-event-class.md)<br /><br /> [SQL:StmtCompleted Event Class](sql-stmtcompleted-event-class.md)<br /><br /> [SQL:StmtRecompile Event Class](sql-stmtrecompile-event-class.md)<br /><br /> [SQL:StmtStarting Event Class](sql-stmtstarting-event-class.md)<br /><br /> [Unprepare SQL Event Class](unprepare-sql-event-class.md)<br /><br /> [XQuery Static Type Event Class](xquery-static-type-event-class.md)|  
|The [User-Configurable Event Category](user-configurable-event-category.md) includes event classes that you can define.|[User-Configurable Event Class](user-configurable-event-class.md)|  
  
## See Also  
 [SQL Server Profiler](../../tools/sql-server-profiler/sql-server-profiler.md)  
  
  