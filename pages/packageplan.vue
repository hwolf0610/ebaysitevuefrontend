<template>
  <div style="background-color:#f4f8f9">
    <!-- <table border="1px" width="100%"><tr><td> -->
    <!-- <div
      class="row"
      style="margin-left:150px;margin-right:150px;margin:50px;background-color:white;"
    >-->
    <div style="margin-right:150px">
    <table
    id="example2"
      border="1px"
      width="100%"
      style="margin: 100px;background-color:white;"
    >
      <thead>Packages</thead>
      <tr>
        <td width="25%">
          <img src="../static/1.png" width="25%" style="flow:left" />
          <div style="text-align: center">
            <p>Sliver</p>
            <p style="color:grey;">
              $
              <span style="font-size:45px">24</span>
            </p>
            <p>per month</p>
            <div> ebay orders<img src="../static/2.png" width="3%" />    </div>
            <div> ebay messages<img src="../static/3.png" width="3%" />    </div>
            <div> No, of listings<img src="../static/3.png" width="3%" />    </div>
            <div> fetch feedbacks<img src="../static/3.png" width="3%" />    </div>
            <div> support center<img src="../static/3.png" width="3%" />    </div>
            <div> Message templates<img src="../static/2.png" width="3%" />    </div>
            <div> Reminders and Alerts<img src="../static/3.png" width="3%" />    </div>
            <div> Extra festures<img src="../static/2.png" width="3%" />    </div>
            <div> Normal Gesture<img src="../static/3.png" width="3%" />    </div>            
            <p>
              <button class="btn btn-success">Edit</button>
            </p>
          </div>
        </td>
        <td width="25%">
          <img src="../static/1.png" width="25%" style="flow:left" />
          <div style="text-align: center">
            <p>Gold</p>
            <p style="color:#fed700;">
              $
              <span style="font-size:45px">34</span>
            </p>
            <p>per month</p>
           <div> ebay orders<img src="../static/2.png" width="3%" />    </div>
            <div> ebay messages<img src="../static/3.png" width="3%" />    </div>
            <div> No, of listings<img src="../static/3.png" width="3%" />    </div>
            <div> fetch feedbacks<img src="../static/2.png" width="3%" />    </div>
            <div> support center<img src="../static/3.png" width="3%" />    </div>
            <div> Message templates<img src="../static/2.png" width="3%" />    </div>
            <div> Reminders and Alerts<img src="../static/3.png" width="3%" />    </div>
            <div> Extra festures<img src="../static/3.png" width="3%" />    </div>
            <div> Normal Gesture<img src="../static/2.png" width="3%" />    </div>  
            <p>
              <button class="btn btn-success">Edit</button>
            </p>
          </div>
        </td>
        <td width="25%">
          <img src="../static/1.png" width="25%" style="flow:left" />
          <div style="text-align: center">
            <p>Platinum</p>
            <p style="color:block;">
              $
              <span style="font-size:45px">45</span>
            </p>
            <p>per month</p>
            <div> ebay orders<img src="../static/2.png" width="3%" />    </div>
            <div> ebay messages<img src="../static/3.png" width="3%" />    </div>
            <div> No, of listings<img src="../static/3.png" width="3%" />    </div>
            <div> fetch feedbacks<img src="../static/2.png" width="3%" />    </div>
            <div> support center<img src="../static/3.png" width="3%" />    </div>
            <div> Message templates<img src="../static/2.png" width="3%" />    </div>
            <div> Reminders and Alerts<img src="../static/3.png" width="3%" />    </div>
            <div> Extra festures<img src="../static/2.png" width="3%" />    </div>
            <div> Normal Gesture<img src="../static/2.png" width="3%" />    </div>  
            <p>
              <button class="btn btn-success">Edit</button>
            </p>
          </div>
        </td>
        <td width="25%">
          <img src="../static/1.png" width="25%" style="flow:left" />
          <div style="text-align: center">
            <p>Diamond</p>
            <p style="color:pink;">
              $
              <span style="font-size:45px">54</span>
            </p>
            <p>per month</p>
            <div> ebay orders<img src="../static/2.png" width="3%" />    </div>
            <div> ebay messages<img src="../static/2.png" width="3%" />    </div>
            <div> No, of listings<img src="../static/2.png" width="3%" />    </div>
            <div> fetch feedbacks<img src="../static/2.png" width="3%" />    </div>
            <div> support center<img src="../static/3.png" width="3%" />    </div>
            <div> Message templates<img src="../static/2.png" width="3%" />    </div>
            <div> Reminders and Alerts<img src="../static/2.png" width="3%" />    </div>
            <div> Extra festures<img src="../static/2.png" width="3%" />    </div>
            <div> Normal Gesture<img src="../static/2.png" width="3%" />    </div>  
            <p>
              <button class="btn btn-success">Edit</button>
            </p>
          </div>
        </td>
        
      </tr>
    </table>
  </div>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo
  }
};
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

/* .container {
  display: flex;
} */

img {
  margin: 6px;
}

#example2 {
  border: 1px solid;
  padding: 10px;
  box-shadow: 5px 10px 8px 10px #888888;
}
</style>
