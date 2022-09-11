<!-- TOP -->
<div class="top">
  <img src="https://datastax-academy.github.io/katapod-shared-assets/images/ds-academy-logo.svg" />
  <div class="scenario-title-section">
    <span class="scenario-title">Cassandra Query Language</span>
    <span class="scenario-subtitle">ℹ️ For technical support, please contact us via <a href="mailto:aleksandr.volochnev@datastax.com">email</a> or <a href="https://dtsx.io/aleks">LinkedIn</a>.</span>
  </div>
</div>

<!-- NAVIGATION -->
<div id="navigation-top" class="navigation-top">
 <a href='command:katapod.loadPage?[{"step":"step9"}]'
   class="btn btn-dark navigation-top-left">⬅️ Back
 </a>
<span class="step-count"> Step 10 of 10</span>
 <a href='command:katapod.loadPage?[{"step":"finish"}]'
    class="btn btn-dark navigation-top-right">Next ➡️
  </a>
</div>

<!-- CONTENT -->

<div class="step-title">CQL vs. SQL</div>

If you are familiar with SQL, CQL may look quite similar. 
Indeed, there are many syntactic similarities between the two languages, but there are also many 
important differences. Here are just a few facts about CQL that highlight some of the differences:

- CQL supports tables with single-row and multi-row partitions
- CQL table primary key consists of a mandatory partition key and an optional clustering key
- CQL does not support referential integrity constraints
- CQL updates or inserts may result in upserts
- CQL queries cannot retrieve data based on an arbitrary table column
- CQL supports no joins or other binary operations
- CQL CRUD operations are executed with a tunable consistency level
- CQL supports lightweight transactions but not ACID transactions

If some of the above facts do not sound familiar, you know that there are more about CQL to learn! 

<!-- NAVIGATION -->
<div id="navigation-bottom" class="navigation-bottom">
 <a href='command:katapod.loadPage?[{"step":"step9"}]'
   class="btn btn-dark navigation-bottom-left">⬅️ Back
 </a>
 <a href='command:katapod.loadPage?[{"step":"finish"}]'
    class="btn btn-dark navigation-bottom-right">Next ➡️
  </a>
</div>

