<!-- TOP -->
<div class="top">
  <img src="https://datastax-academy.github.io/katapod-shared-assets/images/ds-academy-logo.svg" />
  <span class="scenario-title">Cassandra Query Language</span>
  <span class="scenario-subtitle">ℹ️ For technical support, please contact us via <a href="mailto:aleksandr.volochnev@datastax.com">email</a> or <a href="https://dtsx.io/aleks">LinkedIn</a>.</span> 
</div>

<!-- NAVIGATION -->
<div id="navigation-top" class="navigation-top">
 <a href='command:katapod.loadPage?[{"step":"step8"}]'
   class="btn btn-dark navigation-top-left">⬅️ Back
 </a>
<span class="step-count"> Step 9 of 10</span>
 <a href='command:katapod.loadPage?[{"step":"step10"}]'
    class="btn btn-dark navigation-top-right">Next ➡️
  </a>
</div>

<!-- CONTENT -->

<div class="step-title">Delete a row</div>

✅ Finally, delete the row using the CQL `DELETE` statement:
```
DELETE FROM users 
WHERE email = 'joe@datastax.com';

SELECT * FROM users;
```

✅ Deleting another row from the table:

<details>
  <summary>Solution</summary>

```
DELETE FROM users 
WHERE email = 'jen@datastax.com';

SELECT * FROM users;
```

</details>

<!-- NAVIGATION -->
<div id="navigation-bottom" class="navigation-bottom">
 <a href='command:katapod.loadPage?[{"step":"step8"}]'
   class="btn btn-dark navigation-bottom-left">⬅️ Back
 </a>
 <a href='command:katapod.loadPage?[{"step":"step10"}]'
    class="btn btn-dark navigation-bottom-right">Next ➡️
  </a>
</div>

