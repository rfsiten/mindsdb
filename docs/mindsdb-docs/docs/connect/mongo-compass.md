# MindsDB and MongoDB Compass

MongoDB Compass is the GUI for MongoDB. Compass provides detailed schema visualizations, real-time performance metrics, sophisticated querying abilities, and much more. You can download it [here](https://www.mongodb.com/try/download/).


## Connect

First, create a new connection in Compass by clicking the `New Connection` from the left navigation panel.
Next, paste the connection string:

<p align="center">
  <img src="/assets/connect_compass_srv.png" />
</p>

Or, fill in connection fields individualy:

<p align="center">
  <img src="/assets/connect_compassm.png" />
</p>

In the above images we've connected to local MindsDB. Check the option bellow to connect to MindsDB cloud.

=== "Connecting to your MindsDB Cloud account"

    You can connect to your MindsDB Cloud account. To do that, please use the connection details below:<br/>

    ```text
    Hostname: `cloud.mindsdb.com`
    Port: `272018`
    Authentication: `Username / Password`
    Username: *your MindsDB Cloud email*
    Password: *your MindsDB Cloud password*
    ```

    <p align="center">
    <img src="/assets/connect_compass_cloud.png" />
    </p>

## What's Next?

Now that you are all set, we recommend you check out our **Tutorials** and **Community Tutorials** sections, where you'll find various examples of regression, classification, and time series predictions with MindsDB.

To learn more about MindsDB itself, follow the guide on [MindsDB collection structure](/mongo/collection-structure/). Also, don't miss out on the remaining pages from the **MONGO API** section, as they explain a common MQL syntax with examples.

Have fun!
