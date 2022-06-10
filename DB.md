## `DB::table($table, $as = null)`

Begin a fluent query against a database table.

## `DB::query()`

Get a new query builder instance.

## `DB::selectOne($query, $bindings = [], $useReadPdo = true)`

Run a select statement and return a single result.

## `DB::scalar($query, $bindings = [], $useReadPdo = true)`

Run a select statement and return the first column of the first row.

## `DB::selectFromWriteConnection($query, $bindings = [])`

Run a select statement against the database.

## `DB::select($query, $bindings = [], $useReadPdo = true)`

Run a select statement against the database.

## `DB::cursor($query, $bindings = [], $useReadPdo = true)`

Run a select statement against the database and returns a generator.

## `DB::insert($query, $bindings = [])`

Run an insert statement against the database.

## `DB::update($query, $bindings = [])`

Run an update statement against the database.

## `DB::delete($query, $bindings = [])`

Run a delete statement against the database.

## `DB::statement($query, $bindings = [])`

Execute an SQL statement and return the boolean result.

## `DB::affectingStatement($query, $bindings = [])`

Run an SQL statement and get the number of rows affected.

## `DB::unprepared($query)`

Run a raw, unprepared query against the PDO connection.

## `DB::pretend(Closure $callback)`

Execute the given callback in "dry run" mode.

## `DB::withFreshQueryLog($callback)`

Execute the given callback in "dry run" mode.

## `DB::bindvalues($statement, $bindings)`

Bind values to their parameters in the given statement.

## `DB::prepareBindings(array $bindings)`

Prepare the query bindings for execution.

## `DB::logQuery($query, $bindings, $time = null)`

Log a query in the connection's query log.

## `DB::reconnect()`

Reconnect to the database.

## `DB::disconnect()`

Disconnect from the underlying PDO connection.

## `DB::beforeExecuting(Closure $callback)`

Register a hook to be run just before a database query is executed.

## `DB::listen(Closure $callback)`

Register a database query listener with the connection.

## `DB::raw($value)`

Get a new raw query expression.

## `DB::hasModifiedRecords()`

Determine if the database connection has modified any database records.

## `DB::records HaveBeenModified($value = true)`

Indicate if any records have been modified.

## `DB::setRecordModificationState(bool $value)`

Set the record modification state.

## `DB::forgetRecordModificationState()`

Reset the record modification state.

## `DB::useWriteConnectionWhenReading($value = true)`

Indicate that the connection should use the write PDO connection for reads.

## `DB::isDoctrineAvailable()`

Is Doctrine available?

## `DB::getDoctrineColumn($table, $column)`

Get a Doctrine Schema Column instance.

## `DB::getDoctrineschemaManager()`

Get the Doctrine DBAL schema manager for the connection.

## `DB::getDoctrineConnection()`

Get the Doctrine DBAL database connection instance.

## `DB::registerDoctrineType(string $class, string $name, string $type)`

Register a custom Doctrine mapping type.

## `DB::getPdo()`

Get the current PDO connection.

## `DB::getRawPdo()`

Get the current PDO connection parameter without executing any reconnect logic.

## `DB::getReadPdo()`

Get the current PDO connection used for reading.

## `DB::getRawReadPdo()`

Get the current read PDO connection parameter.

## `DB::setPdo($pdo)`

Set the PDO connection.

## `DB::setReadPdo($pdo)`

Set the PDO connection used for reading.

## `DB::setReconnector(callable $reconnector)`

Set the reconnect instance on the connection.

## `DB::getName()`

Get the database connection name.

## `DB::getNameWithReadWriteType()`

Get the database connection full name.

## `DB::getConfig($option = null)`

Get an option from the configuration options.

## `DB::getDriverName()`

Get the PDO driver name.

## `DB::getQueryGrammar()`

Get the query grammar used by the connection.

## `DB::setQueryGrammar(Query\Grammars\Grammar $grammar)`

Set the query grammar used by the connection.

## `DB::getPostProcessor()`

Get the query post processor used by the connection.

## `DB::setPostProcessor(Processor $processor)`

Set the query post processor used by the connection.

## `DB::getEventDispatcher()`

Get the event dispatcher used by the connection.

## `DB::setEventDispatcher(Dispatcher $events)`

Set the event dispatcher instance on the connection.

## `DB::unsetEventDispatcher()`

Unset the event dispatcher for this connection.

## `DB::setTransactionManager($manager)`

Set the transaction manager instance on the connection.

## `DB::unsetTransactionManager()`

Unset the transaction manager for this connection.

## `DB::getQueryLog()`

Get the connection query log.

## `DB::flushQueryLog()`

Clear the query log.

## `DB::enableQueryLog()`

Enable the query log on the connection.

## `DB::disableQueryLog()`

Disable the query log on the connection.

## `DB::logging()`

Determine whether we're logging queries.
