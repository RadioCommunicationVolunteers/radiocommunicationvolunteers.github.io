---
title: Volunteers Wanted
linkTitle: Volunteers
description: Giving back to your local community.
menu: { main: { weight: 10 } } 
---

{{% blocks/cover
  title="Volunteers Wanted"
  height="auto td-below-navbar"
  color="bg-info bg-gradient td-below-navbar"
%}}

<!-- prettier-ignore -->
{{% _param description %}}
{.display-6}

{{% blocks/button-modal
  caption="Apply Now"
  title="Volunteer Application"
  emailTo="techiee09@gmail.com"
%}}
  <div class="row mb-4">
    <div class="col-sm-3">
      <div class="input-group date" data-provide="datepicker">
        <div class="input-group-prepend">
            <span class="input-group-text" id="dateLabel">Date</span>
        </div>
        <input id="datepicker1" type="text" class="form-control" aria-describedby="dateLabel" />
        <div class="input-group-addon">
            <span class="glyphicon glyphicon-th"></span>
        </div>
      </div>
    </div>
    <div class="col-sm-9">
      <div class="input-group">
        <div class="input-group-prepend">
            <span class="input-group-text" id="callsignLabel">Callsign</span>
        </div>
        <input id="callsign" type="text" class="form-control" aria-describedby="callsignLabel" />
        <div class="input-group-append">
          <button class="btn btn-outline-secondary dropdown-toggle" type="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">class</button>
          <div class="dropdown-menu">
            <a class="dropdown-item" href="#">Tech</a>
            <a class="dropdown-item" href="#">General</a>
            <a class="dropdown-item" href="#">Extra</a>
            <div role="separator" class="dropdown-divider"></div>
            <a class="dropdown-item" href="#">None</a>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="row mb-4">
    <div class="col-sm-12">
      <div class="input-group">
        <div class="input-group-prepend">
            <span class="input-group-text" id="emailFromLabel">Name</span>
        </div>
        <input type="text" id="formName" class="form-control" />
      </div>
      <div class="row">
        <div class="col-sm-4 text-center">
          <small id="formFirstNameHelp" class="form-text text-muted"><i>(First)</i></small>
        </div>
        <div class="col-sm-4 text-center">
          <small id="formMiddleNameHelp" class="form-text text-muted"><i>(Middle)</i></small>
        </div>
        <div class="col-sm-4 text-center">
          <small id="formLastNameHelp" class="form-text text-muted"><i>(Last)</i></small>
        </div>
      </div>
    </div>
  </div>
  <div class="row mb-4">
    <div class="col-sm-12">
      <div class="input-group">
        <div class="input-group-prepend">
            <span class="input-group-text" id="AddressLabel">Address</span>
        </div>
        <textarea id="formAddress" class="form-control" aria-label="With Address"></textarea>
      </div>
    </div>
  </div>
  <div class="row mb-4">
    <div class="col-sm-6">
      <div class="input-group">
        <div class="input-group-prepend">
          <span class="input-group-text" id="formCityLabel">City</span>
        </div>
        <input type="text" id="formCity" class="form-control" />
      </div>
    </div>
    <div class="col-sm-2">
      <div class="input-group">
        <div class="input-group-prepend">
          <span class="input-group-text" id="formStateLabel">State</span>
        </div>
        <input type="text" id="formState" class="form-control" />
      </div>
    </div>
    <div class="col-sm-4">
      <div class="input-group">
        <div class="input-group-prepend">
          <span class="input-group-text" id="formZipCodeLabel">Zip Code</span>
        </div>
        <input type="text" id="formZipCode" class="form-control" />
      </div>
    </div>
  </div>
  <div class="row mb-4">
    <div class="col-sm-6">
      <div class="input-group">
        <div class="input-group-prepend">
          <span class="input-group-text" id="formPhoneLabel">Phone Number</span>
        </div>
        <input type="text" id="formPhone" class="form-control" />
      </div>
    </div>
    <div class="col-sm-6">
      <div class="input-group">
        <div class="input-group-prepend">
          <span class="input-group-text"></span>
        </div>
        <input type="text" class="form-control" />
      </div>
    </div>
  </div>
{{% /blocks/button-modal %}}

{{% /blocks/cover %}}

{{% blocks/lead color="white" %}}

Goldydocs is a sample site using the [Docsy](https://github.com/google/docsy)
Hugo theme that shows what it can do and provides you with a template site
structure. It’s designed for you to clone and edit as much as you like. See the
different sections of the documentation and site for more ideas.

{{% /blocks/lead %}}

{{% blocks/section type="row text-center h1" %}}

This is another section with center alignment

{{% /blocks/section %}}

{{% blocks/section type="h1" %}}

This is another section with default alignment

{{% /blocks/section %}}
