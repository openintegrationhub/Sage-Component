# <img src="./sage.jpg" width="250" height="250"> Sage People API OIH Connector

## Description

A generated OIH connector for the Sage People API API (version 4.7).

Generated from: https://{domain}/services/apexrest/spapi/v4<br/>
Generated at: 2021-03-09T15:07:48+01:00

## API Description

The Sage People API provides a means to extract data from the Sage People application.<br/>
<br/>
# Authorization<br/>
<br/>
You need a bearer token to authenticate with Sage People API, see the Get Started section for more information.<br/>
<br/>
# Headers<br/>
<br/>
Requests to Sage People API need the following header: `Accept: application/json`<br/>
<br/>
<!-- ReDoc-Inject: <security-definitions> --><br/>
<br/>
&nbsp;<br/>

## Authorization

Supported authorization schemes:
- Bearer Token

## Actions

### Get Salaries
> Retrieve a paginated list of salaries<br/>

*Tags:* `Salary`

#### Input Parameters
* `marker` - _optional_ - Optional parameter used to retrieve the next page of data. Gets page of data after provided salary id.<br/>
* `$filter` - _optional_ - Optional parameter used to filter the data returned by the Api.<br/>

### Get Employees
> Retrieve a paginated list of employees<br/>

*Tags:* `Employee`

#### Input Parameters
* `marker` - _optional_ - Optional parameter used to retrieve the next page of data. Gets page of data after provided employee id.<br/>
* `$filter` - _optional_ - Optional parameter used to filter the data returned by the Api.<br/>

### Get Employee by Id
> Retrieve a single employee<br/>

*Tags:* `Employee`

#### Input Parameters
* `employeeId` - _required_ - Required parameter to identify an employee<br/>

### Add Pay Details
> Add new pay details for a single employee<br/>

*Tags:* `Employee`

#### Input Parameters
* `employeeId` - _required_ - Required parameter to identify an employee<br/>

### Get Absences
> Retrieve a paginated list of absences<br/>

*Tags:* `Absence`

#### Input Parameters
* `marker` - _optional_ - Optional parameter used to retrieve the next page of data. Gets page of data after provided absence id.<br/>
* `$filter` - _optional_ - Optional parameter used to filter the data returned by the Api.<br/>

### Get Bonuses
> Retrieve a paginated list of bonuses<br/>

*Tags:* `Bonus`

#### Input Parameters
* `marker` - _optional_ - Optional parameter used to retrieve the next page of data. Gets page of data after provided bonus id.<br/>
* `$filter` - _optional_ - Optional parameter used to filter the data returned by the Api.<br/>

### Get Absence Balances
> Retrieve a paginated list of absence balances<br/>

*Tags:* `Absence Balance`

#### Input Parameters
* `marker` - _optional_ - Optional parameter used to retrieve the next page of data. Gets page of data after provided absence balance id.<br/>
* `$filter` - _optional_ - Optional parameter used to filter the data returned by the Api.<br/>

### Get Timesheets
> Retrieve a paginated list of timesheets<br/>

*Tags:* `Timesheet`

#### Input Parameters
* `marker` - _optional_ - Optional parameter used to retrieve the next page of data. Gets page of data after provided timesheet id.<br/>
* `$filter` - _optional_ - Optional parameter used to filter the data returned by the Api.<br/>

## License

: sage<br/>
                    <br/>

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
