## Create an Investor

#### Story -
> As an investor, I visit the website / app, So that I can sign up and enter details to begin investing.

**If the investor is already KYC compliant -**

|     Steps    |     Method       |    Reference    |
|--------------|------------------|-----------------|
| Create an investor in the system | POST | [Create investor](https://fintechprimitives.com/api/#post-create-investor) |
| Create an investment account for the investor | POST | [Create investment account](https://fintechprimitives.com/api/#post-create-investment-account) |


`GET http://{{ window.targetResourceName }}.example.com/api/onb/investors`

<pre><code>GET http://{{ window.targetResourceName }}.example.com/api/onb/investors</code></pre>

--------------------------------------------------------------------------------
<script>
  let urlParams = new URLSearchParams(window.location.search);
  window.targetResourceName = urlParams.get('target-res');
</script>
