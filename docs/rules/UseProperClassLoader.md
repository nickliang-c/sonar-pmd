# UseProperClassLoader
**Category:** `pmd`<br/>
**Rule Key:** `pmd:UseProperClassLoader`<br/>


-----

In J2EE getClassLoader() might not work as expected. Use Thread.currentThread().getContextClassLoader() instead.
