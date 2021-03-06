---
title: "Tables"
permalink: docs/:path
excerpt: 'Tables organize information in columns and rows. Table cells can be aligned to the left, center, or right. Stripes can also be added to tables to differentiate between rows.'
---

# {{ page.title }}
{{ page.excerpt }}


***


### Standard

{% capture table_default %}
<table class="table">
    <thead>
        <tr>
            <th class="is-sorted">Date</th>
            <th class="is-right">Time</th>
            <th class="is-sorted is-sorted__ascend">User</th>
            <th>Role</th>
            <th>Cause</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>04/14/2017</th>
            <td class="is-right">1:34 PDT</td>
            <td>yby.jupiter</td>
            <td>
            <div class="input has-arrow is-medium">
                <select name="">
                <option value="" disabled="" selected="">Select your option</option>
                <option value="">Value 1</option>
                <option value="">Value 2</option>
                <option value="">Value 3</option>
                </select>
            </div>
            </td>
            <td>jira123</td>
        </tr>
        <tr>
            <th>04/14/2017</th>
            <td class="is-right">19:34 PDT</td>
            <td>yby.jupiter</td>
            <td>Admin</td>
            <td>jira123</td>
        </tr>
    </tbody>
</table>
{% endcapture %}
{% include code-snippet.html code=table_default url='table_default.html' %}


***


### Striped

{% capture table_striped %}
<table class="table is-striped">
  <thead>
    <tr>
      <th class="is-sorted is-sorted__descend">Name</th>
      <th>Domain</th>
      <th>User</th>
      <th>Date</th>
      <th class="is-center">Delete All</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th><a href="#">AC::CGQ1::BULLETMAIL_CLIENTS</a></th>
      <td><a href="#">pes.acl.greylist</a></td>
      <td>Chas Turansky</td>
      <td class="is-mono">09/27/2020</td>
      <td class="is-center"><a href="#"><span class="d-icon d-trash is-small"></span></a></td>
    </tr>
    <tr>
      <th><a href="#">BULLETMAIL_CLIENTS</a></th>
      <td><a href="#">pes.acl.greylist</a></td>
      <td>Chas Turansky</td>
      <td class="is-mono">09/27/2020</td>
      <td class="is-center"><a href="#"><span class="d-icon d-trash is-small"></span></a></td>
    </tr>
    <tr>
      <th><a href="#">AC::CGQ1::BULLETMAIL_CLIENTS</a></th>
      <td><a href="#">pes.acl.greylist</a></td>
      <td>Chas Turansky</td>
      <td class="is-mono">09/27/2020</td>
      <td class="is-center"><a href="#"><span class="d-icon d-trash is-small"></span></a></td>
    </tr>
    <tr>
      <th><a href="#">AC::CGQ1::BULLETMAIL_CLIENTS</a></th>
      <td><a href="#">pes.acl.greylist</a></td>
      <td>Chas Turansky</td>
      <td class="is-mono">09/27/2020</td>
      <td class="is-center"><a href="#"><span class="d-icon d-trash is-small"></span></a></td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <th><a href="#">Footer</a></th>
      <td><a href="#">pes.acl.greylist</a></td>
      <td>Chas Turansky</td>
      <td class="is-mono">09/27/2020</td>
      <td class="is-center"><a href="#"><i class="d-icon d-trash is-small"></i></a></td>
    </tr>
  </tfoot>
</table>
{% endcapture %}
{% include code-snippet.html code=table_striped url='table_striped.html' height='300'%}


***


### Cards

{% capture table_cards %}
<table class="table is-cards">
  <thead>
    <tr>
      <th class="is-sorted is-sorted__descend">Name</th>
      <th>Domain</th>
      <th>User</th>
      <th>Date</th>
      <th class="is-center">Delete All</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th><a href="#">AC::CGQ1::BULLETMAIL_CLIENTS</a></th>
      <td><a href="#">pes.acl.greylist</a></td>
      <td>Chas Turansky</td>
      <td class="is-mono">09/27/2020</td>
      <td class="is-center"><a href="#"><span class="d-icon d-trash is-small"></span></a></td>
    </tr>
    <tr>
      <th><a href="#">BULLETMAIL_CLIENTS</a></th>
      <td><a href="#">pes.acl.greylist</a></td>
      <td>Chas Turansky</td>
      <td class="is-mono">09/27/2020</td>
      <td class="is-center"><a href="#"><span class="d-icon d-trash is-small"></span></a></td>
    </tr>
    <tr>
      <th><a href="#">AC::CGQ1::BULLETMAIL_CLIENTS</a></th>
      <td><a href="#">pes.acl.greylist</a></td>
      <td>Chas Turansky</td>
      <td class="is-mono">09/27/2020</td>
      <td class="is-center"><a href="#"><span class="d-icon d-trash is-small"></span></a></td>
    </tr>
    <tr>
      <th><a href="#">AC::CGQ1::BULLETMAIL_CLIENTS</a></th>
      <td><a href="#">pes.acl.greylist</a></td>
      <td>Chas Turansky</td>
      <td class="is-mono">09/27/2020</td>
      <td class="is-center"><a href="#"><span class="d-icon d-trash is-small"></span></a></td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <th><a href="#">Footer</a></th>
      <td><a href="#">pes.acl.greylist</a></td>
      <td>Chas Turansky</td>
      <td class="is-mono">09/27/2020</td>
      <td class="is-center"><a href="#"><i class="d-icon d-trash is-small"></i></a></td>
    </tr>
  </tfoot>
</table>
{% endcapture %}
{% include code-snippet.html code=table_cards url='table_cards.html' height='360'%}


***


### Alignment

{% capture table_alignment %}
<table class="table">
    <tbody>
        <tr>
            <th>Default</th>
            <th class="is-center">Center</th>
            <th class="is-right">Right</th>
        </tr>
        <tr>
            <td><span class="d-icon d-text-left"></span></td>
            <td class="is-center"><span class="d-icon d-text-center"></span></td>
            <td class="is-right"><span class="d-icon d-text-right"></span></td>
        </tr>
    </tbody>
</table>
{% endcapture %}
{% include code-snippet.html code=table_alignment url='table_alignment.html' %}


***


### Freeze

{% capture table_freeze %}
<div class="table-container table-container__freeze">
  <table class="table">
    <thead>
      <tr>
        <th class="is-sorted is-sorted__descend">
          <div class="checkbox">
            <input id="denali-checkbox-0" type="checkbox" value="value1" data-partial />
            <label for="denali-checkbox-0"></label>
          </div>
          Name
        </th>
        <th>Domain</th>
        <th>User</th>
        <th>Date</th>
        <th class="is-center">Delete All</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th>
          <div class="checkbox">
            <input id="denali-checkbox-1" type="checkbox" value="value1" checked />
            <label for="denali-checkbox-1"></label>
          </div>
          BULLETMAIL_CLIENTS
        </th>
        <td><a href="#">pes.acl.greylist</a></td>
        <td>Chas Turansky</td>
        <td class="is-mono">09/27/2020</td>
        <td class="is-center"><a href="#"><span class="d-icon d-trash is-small"></span></a></td>
      </tr>
      <tr>
        <th>
          <div class="checkbox">
            <input id="denali-checkbox-2" type="checkbox" value="value1" />
            <label for="denali-checkbox-2"></label>
          </div>
          CLIENTS
        </th>
        <td><a href="#">pes.acl.greylist</a></td>
        <td>Chas Turansky</td>
        <td class="is-mono">09/27/2020</td>
        <td class="is-center"><a href="#"><span class="d-icon d-trash is-small"></span></a></td>
      </tr>
      <tr>
        <th>
          <div class="checkbox">
            <input id="denali-checkbox-3" type="checkbox" value="value1" />
            <label for="denali-checkbox-3"></label>
          </div>
          MAIL_USER
        </th>
        <td><a href="#">pes.acl.greylist</a></td>
        <td>Chas Turansky</td>
        <td class="is-mono">09/27/2020</td>
        <td class="is-center"><a href="#"><span class="d-icon d-trash is-small"></span></a></td>
      </tr>
      <tr>
        <th>
          <div class="checkbox">
            <input id="denali-checkbox-4" type="checkbox" value="value1" checked />
            <label for="denali-checkbox-4"></label>
          </div>
          TEST_CLIENTS
        </th>
        <td><a href="#">pes.acl.greylist</a></td>
        <td>Chas Turansky</td>
        <td class="is-mono">09/27/2020</td>
        <td class="is-center"><a href="#"><span class="d-icon d-trash is-small"></span></a></td>
      </tr>
    </tbody>
    <tfoot>
      <tr>
        <th><a href="#">Footer</a></th>
        <th><a href="#">pes.acl.greylist</a></th>
        <td>Chas Turansky</td>
        <td class="is-mono">09/27/2020</td>
        <th class="is-center"><a href="#"><i class="d-icon d-trash is-small"></i></a></th>
      </tr>
    </tfoot>
  </table>
</div>
{% endcapture %}
{% include code-snippet.html code=table_freeze url='table_freeze.html' %}


***


### Variables
You can use these variables in a `override.css` file to customize this component.

|Variable Name|CSS Property|
| - | - |
|`$table-border-radius`| border-radius|
|`$table-row-default-height`| height|
|`$table-row-condensed-height`| height|
|`$table-row-expanded-height`|  height|
|`$table-row-border-bottom`| border-bottom|
|`$table-row-padding`| padding|
|`$table-header-text-color`| color|
|`$table-header-text-size`|  font-size|
|`$table-header-text-transform`|  text-transform|
|`$table-header-text-weight`| font-weight|
|`$table-header-padding`| padding|
|`$table-header-border-bottom`| border-bottom|
|`$table-header-sort-text-weight`| font-weight|
|`$table-footer-bg-color`| background|
|`$table-striped-row-bg-color`| background|
|`$table-cards-spacing`| padding|
|`$table-cards-border`| border|