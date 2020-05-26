<template>
  <div class="signup-form" >
      <h2>Register</h2>
      <p>Create your account</p>
      <hr />
      <div class="form-group">
        <div class="input-group">
          <span class="input-group-addon">
            <i class="fa fa-user"></i>
          </span>
          <input
            type="text"
            class="form-control"
            name="username"
            placeholder="Username"
            required="required"
          />
        </div>
      </div>
      <div class="form-group">
        <div class="input-group">
          <span class="input-group-addon">
            <i class="fa fa-paper-plane"></i>
          </span>
          <input
            type="email"
            class="form-control"
            name="email"
            placeholder="Email Address"
            required="required"
          />
        </div>
      </div>
      <div class="form-group">
        <div class="input-group">
          <span class="input-group-addon">
            <i class="fa fa-lock"></i>
          </span>
          <input
            type="text"
            class="form-control"
            name="password"
            placeholder="Password"
            required="required"
          />
        </div>
      </div>
      <div class="form-group">
        <div class="input-group">
          <span class="input-group-addon">
            <i class="fa fa-lock"></i>
            <i class="fa fa-check"></i>
          </span>
          <input
            type="text"
            class="form-control"
            name="confirm_password"
            placeholder="Confirm Password"
            required="required"
          />
        </div>
      </div>

      <div class="form-group">
        <button type="submit" class="btn btn-primary btn-lg">Create account</button>
        <div class="text-center">
          Already have an account?
          <a href="#">Login here</a>
        </div>
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


.form-control, .form-control:focus, .input-group-addon {
		border-color: #e1e1e1;
	}
    .form-control, .btn {        
        border-radius: 3px;
width:100%; }
	.signup-form {
		width: 390px;
		margin: 0 auto;
		padding: 30px 0;
	}
    .signup-form form {
		color: #999;
		border-radius: 3px;
    	margin-bottom: 15px;
        background: #fff;
        box-shadow: 0px 2px 2px rgba(0, 0, 0, 0.3);
        padding: 30px;
    }
	.signup-form h2 {
		color: #333;
		font-weight: bold;
        margin-top: 0;
    }
    .signup-form hr {
        margin: 0 -30px 20px;
    }
	.signup-form .form-group {
		margin-bottom: 20px;
	}
	.signup-form label {
		font-weight: normal;
		font-size: 13px;
	}
	.signup-form .form-control {
		min-height: 38px;
		box-shadow: none !important;
	}	
	.signup-form .input-group-addon {
		max-width: 42px;
		text-align: center;
	}
	.signup-form input[type="checkbox"] {
		margin-top: 2px;
	}   
    .signup-form .btn{        
        font-size: 16px;
        font-weight: bold;
		background: #19aa8d;
		border: none;
		min-width: 140px;
    }
	.signup-form .btn:hover, .signup-form .btn:focus {
		background: #179b81;
        outline: none;
	}
	.signup-form a {
		color: #fff;	
		text-decoration: underline;
	}
	.signup-form a:hover {
		text-decoration: none;
	}
	.signup-form form a {
		color: #19aa8d;
		text-decoration: none;
	}	
	.signup-form form a:hover {
		text-decoration: underline;
	}
	.signup-form .fa {
		font-size: 21px;
	}
	.signup-form .fa-paper-plane {
		font-size: 18px;
	}
	.signup-form .fa-check {
		color: #fff;
		left: 17px;
		top: 18px;
		font-size: 7px;
		position: absolute;
	}
</style>
