<!-- TOP -->
<div class="top">
  <img class="scenario-academy-logo" src="https://datastax-academy.github.io/katapod-shared-assets/images/ds-academy-2023.svg" />
  <div class="scenario-title-section">
    <span class="scenario-title">Install and Start<br>Apache Cassandra™</span>
    <span class="scenario-subtitle">ℹ️ For technical support, please contact us via <a href="mailto:academy@datastax.com">email</a>.</span>
  </div>
</div>

<!-- NAVIGATION -->
<div id="navigation-top" class="navigation-top">
 <a href='command:katapod.loadPage?[{"step":"intro"}]'
   class="btn btn-dark navigation-top-left">⬅️ Back
 </a>
<span class="step-count"> Step 2 of 7</span>
 <a href='command:katapod.loadPage?[{"step":"step3"}]' 
    class="btn btn-dark navigation-top-right">Next ➡️
  </a>
</div>

<!-- CONTENT -->

<div class="step-title">Download and extract Cassandra</div>

There are multiple ways to install Cassandra:
- Linux package managers
- Docker
- Tarball


✅ Download the Cassandra tarball from an Apache CDN:
```
curl https://dlcdn.apache.org/cassandra/4.1.0/apache-cassandra-4.1.0-bin.tar.gz \
        --output apache-cassandra-4.1.0-bin.tar.gz
```

✅ View the downloaded tarball:
```
ls -l
```

✅ Extract tarball:
```
tar xf apache-cassandra-4.1.0-bin.tar.gz
```

The directory should now contain the tarball and the `apache-cassandra-4.1.0` directory

✅ View the directory:
```
ls -l
```

<!-- NAVIGATION -->
<div id="navigation-bottom" class="navigation-bottom">
 <a href='command:katapod.loadPage?[{"step":"intro"}]'
   class="btn btn-dark navigation-bottom-left">⬅️ Back
 </a>
 <a href='command:katapod.loadPage?[{"step":"step2"}]'
    class="btn btn-dark navigation-bottom-right">Next ➡️
  </a>
</div>
