# jython-fdmee-autotest

**Jython version: 2.7.0**

Simply package that helps test jython code with FDMEE API calls localy

[ ] Logs Calls like logDebug (logging package)
[ ] DB work
[ ] Mock FDMEE base sql tables with structure


## Functions to realize:
* BigDecimal getPOVLocation(BigDecimal pLoadId)
* ResultSet getCategoryList()
* String getCategoryMap(BigDecimal pCatKey, String pApplicationName)
* ResultSet getPeriodList() 
* Map getPeriodDetail(Date pPeriodKey, String pApplicationName)
* int executeDML(String query, Object[] parameters, boolean commitTransaction) 
* void commitTransaction()
* void log(String pLogMessage)
* void logDebug(String pLogMessage)
* void logInfo(String pLogMessage)
* void logWarn(String pLogMessage)
* void logError(Sring pLogMessage)
* void logFatal(String pLogMessage)
* void logDB(String pEntityType, String pEntityName, int pLogSequence, String pLogMessage)
* void rollbackTransaction()
* ResultSet executeQuery(String query, Object[] parameters)
* ResultSet executeQuery(String query, Object[] parameters, int batchSize) 
* ResultSet getLocationDetails(BigDecimal pPartitionKey) 
* ResultSet getRuleDetails(BigDecimal pRuleId) 
* ResultSet getImportFormatDetails(String pImpGroupKey)
* ResultSet getImportFormatMapDetails(String pImpGroupKey)
* BigDecimal getPOVCategory(BigDecimal pLoadId)
* initializeDevMode(Connection pConnection)
* Date getPOVStartPeriod(BigDecimal pLoadId)
* Date getPOVEndPeriod(BigDecimal pLoadId)
* String getPOVDataValue(BigDecimal pPartitionKey)

