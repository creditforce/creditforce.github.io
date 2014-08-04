---
layout: page
title: Sign Up
permalink: /signup/
id: signup
---

<div class="container">
  <div class="row header">
    <div class="col-md-12">
      <h4>Set up your new account today.</h4>
      <p>
        30-day money-back guarantee that starts after your first payment.
      </p>
    </div>
  </div>
  <div class="row">
    <div class="col-md-12">
      <div class="wrapper clearfix">
        <div class="formy">
          <div class="row">
            <div class="col-md-12">
              <form role="form">
                <div class="form-group">
                    <label for="name">Your name</label>
                    <input type="text" class="form-control" id="name" />
                  </div>
                  <div class="form-group">
                    <label for="email">Email address</label>
                    <input type="email" class="form-control" id="email" />
                  </div>
                  <div class="form-group">
                    <label for="password">Password</label>
                    <input type="password" class="form-control" id="password" />
                  </div>
                  <div class="checkbox">
                    <label>
                        <input type="checkbox"> You have read & agree to the 
                        <a href="#">Terms of service</a>.
                    </label>
                  </div>
                  <div class="submit">
                    <a href="index.html" class="button-clear">
                      <span>Create my account</span>
                    </a>
                  </div>
              </form>
            </div>
          </div>            
        </div>
      </div>
      <div class="already-account">
        Already have an account?
        <a href="http://login.salesforce.com" data-toggle="popover" data-placement="top" data-content="Go to sign in!" data-trigger="manual">Sign in here</a>
      </div>
    </div>
  </div>
</div>

<script type="text/javascript">
  $(function () {
    $(".already-account a").popover();
    $(".already-account a").popover('show');
  });
</script>