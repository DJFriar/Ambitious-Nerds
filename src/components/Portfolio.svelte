<script>
  
</script>

<main>
	<!-- <h1><span class='ambitious'>ambitious</span><span class='Nerds'>Nerds</span></h1> -->
  <p class="intro">We build software applications and web sites. Below is a small portfolio of our work.</p>

  <div class="limiter">
    <div class="container-table100">
      <div class="wrap-table100">
        <div class="table100">
          <table>
            <thead>
              <tr class="table100-head">
                <th class="column1">Project</th>
                <th class="column2">Description</th>
                <th class="column3">Platform</th>
                <th class="column4">Link</th>
              </tr>
            </thead>
            <tbody>
                <tr>
                  <td class="column1">Butter & Saffron Catering Co</td>
                  <td class="column2">Website for a catering company located in Plano, Texas.</td>
                  <td class="column3">Web</td>
                  <td class="column4"><a href="https://www.butterandsaffron.com">Butter & Saffron</a></td>
                </tr>
                <tr>
                  <td class="column1">Mileage Mania</td>
                  <td class="column2">A website platform to facilitate submitting and tracking of required rally materials.</td>
                  <td class="column3">Web</td>
                  <td class="column4"><a href="https://mm.ambitiousnerds.com">Mileage Mania</a></td>
                </tr>
                <tr>
                  <td class="column1">Tour of Honor</td>
                  <td class="column2">A ground up re-write of the Tour of Honor website, Android and iOS apps. The new site will allow 
                    for a much more streamlined rider submission workflow, and more importantlt drastically reduce the effort needed to score submissions.</td>
                  <td class="column3">Web</td>
                  <td class="column4">Coming Soon</td>
                </tr>
                <tr>
                  <td class="column1">ambitiousNerds YouTube Channel</td>
                  <td class="column2">A collection of videos relating to development, programming, and remote work.</td>
                  <td class="column3">YouTube</td>
                  <td class="column4"><a href="/YouTube">YouTube Posts</a></td>
                </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
  </div>
</main>

<style>
  .intro {
		text-align: center;
		padding: 1em;
		margin: 0 auto;
	}

  h1 {
		/* color: #FF6347; */
		font-size: 4em;
		font-weight: 100;
	}
	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
  .tiny-text {
    font-size: 8px;
  }
.container-table100 {
    width: 100%;
    min-height: 30vh;

    display: -webkit-box;
    display: -webkit-flex;
    display: -moz-box;
    display: -ms-flexbox;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    padding:33px 30px
}

.wrap-table100 {
    width:1170px
}

table {
    border-spacing: 1;
    border-collapse: collapse;
    background: #fff;
    border-radius: 10px;
    overflow: hidden;
    width: 100%;
    margin: 0 auto;
    position:relative
}

table * {
    position:relative
}

table td, table th {
    padding-left:8px
}

table thead tr {
    height: 60px;
    background:#36304a
}

table tbody tr {
    height:50px
}

table tbody tr:last-child {
    border:0
}

table td, table th {
    text-align:left
}

table td.l, table th.l {
    text-align:right
}

table td.c, table th.c {
    text-align:center
}

table td.r, table th.r {
    text-align:center
}

.table100-head th {
    font-size: 18px;
    color: #fff;
    line-height: 1.2;
    font-weight:unset
}

tbody tr:nth-child(even) {
    background-color:#f5f5f5
}

tbody tr {
    font-size: 15px;
    color: gray;
    line-height: 1.2;
    font-weight:unset
}

tbody tr:hover {
    color: #555;
    background-color: #f5f5f5;
    cursor:pointer
}

.column1 {
    width: 70px;
    padding-left:40px
}

.column2 {
    width:200px
}

.column3 {
    width:70px
}

.column4 {
    width: 110px;
}

.column5 {
    width: 170px;
    text-align:right
}

.column6 {
    width: 222px;
    text-align: right;
    padding-right:62px
}

@media screen and (max-width: 992px) {
    table {
        display:block
    }

    table > *, table tr, table td, table th {
        display:block
    }

    table thead {
        display:none
    }

    table tbody tr {
        height: auto;
        padding:37px 0
    }

    table tbody tr td {
        padding-left: 40% !important;
        margin-bottom:24px
    }

    table tbody tr td:last-child {
        margin-bottom:0
    }

    table tbody tr td:before {
        font-family: OpenSans-Regular;
        font-size: 14px;
        color: #999;
        line-height: 1.2;
        font-weight: unset;
        position: absolute;
        width: 40%;
        left: 30px;
        top:0
    }

    table tbody tr td:nth-child(1):before {
        content: "Date"
    }

    table tbody tr td:nth-child(2):before {
        content: "Order ID"
    }

    table tbody tr td:nth-child(3):before {
        content: "Name"
    }

    table tbody tr td:nth-child(4):before {
        content: "Price"
    }

    table tbody tr td:nth-child(5):before {
        content: "Quantity"
    }

    table tbody tr td:nth-child(6):before {
        content: "Total"
    }

    .column4, .column5, .column6 {
        text-align:left
    }

    .column4, .column5, .column6, .column1, .column2, .column3 {
        width:100%
    }

    tbody tr {
        font-size:14px
    }
}

@media (max-width: 576px) {
    .container-table100 {
        padding-left: 15px;
        padding-right: 15px
    }
}
</style>