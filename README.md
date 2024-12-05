# SecurityTalk

HTTP/1.1 200 OK
Server: nginx/1.18.0 (Ubuntu)
Date: Thu, 05 Dec 2024 17:54:00 GMT
Content-Type: text/html; charset=utf-8
Connection: keep-alive
X-Frame-Options: DENY
Vary: Cookie
X-Content-Type-Options: nosniff
Referrer-Policy: same-origin
Cross-Origin-Opener-Policy: same-origin
Set-Cookie: csrftoken=vt1iG7M1yV6gj78xHVQi69l76T2DH3HZ; expires=Thu, 04 Dec 2025 17:54:00 GMT; Max-Age=31449600; Path=/; SameSite=Lax
Content-Length: 22619


<!DOCTYPE html>
<html lang="en">

<head>
  <!-- Required meta tags -->
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <title>Admin Panel</title>
  <!-- plugins:css -->
  <link rel="stylesheet" href="/static/vendors/mdi/css/materialdesignicons.min.css">
  
  <!-- endinject -->
  <!-- plugin css for this page -->
  
  <!-- End plugin css for this page -->
  <!-- inject:css -->
  <link rel="stylesheet" href="/static/css/styles.css">
  <!-- endinject -->
  
  
  
  <link href="/static/css/bootstrap.minn.css" rel="stylesheet">

  
  <!-- Font Awesome CSS -->
  

  <!-- Custom CSS to move sidebar up -->
  <style>
    .sidebar {
      margin-top: -49px; /* Adjust this value as needed */
    }
        .navbar {
            position: relative;
            border-bottom: 1px ridge white; /* Change this color to your desired border color */
            box-shadow: 0 2px 2px rgba(0, 0, 0, 0.1); /* Optional: Add a subtle shadow for depth */
        }
        
        .navbar::after {
            content: '';
            position: absolute;
            bottom: -2px; /* Adjust based on the desired blur spread */
            left: 0;
            width: 100%;
            height: 5px; /* Adjust based on the desired blur spread */
            background: rgba(0, 123, 255, 0.3); /* Same color as the border with transparency */
            filter: blur(8px); /* Adjust blur intensity */
            pointer-events: none;
            z-index: -1; /* Place behind the navbar */
        }
</style>
</head>

<body>

  <nav class="navbar navbar-expand-lg navbar-dark bg-white py-3 px-4">
    <a href="/" class="navbar-brand p-0">
        <h1 class="text-primary m-0"><i class="fas fa-donate me-3"></i>Finovo Bank</h1>
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false" style="color:black">
            Admin
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="/accounts/logout/">Logout</a>
          </div>
        </li>
      </ul>
    </div>
  </nav>
  <!-- partial -->
  <div class="container-fluid page-body-wrapper">
    <nav class="sidebar sidebar-offcanvas" id="sidebar">
      <ul class="nav">
        <li class="nav-item">
          <a class="nav-link" href="/adminpanel/">
            <i class="mdi mdi-home menu-icon"></i>
            <span class="menu-title">Dashboard</span>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/blog-posts/">
            <i class="mdi mdi-pencil menu-icon"></i>
            <span class="menu-title">Manage Blogs</span>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/contact-messages/">
            <i class="mdi mdi-email menu-icon"></i>
            <span class="menu-title">Contact Messages</span>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/admin_users/">
            <i class="mdi mdi-account-multiple menu-icon"></i>
            <span class="menu-title">Accounts</span>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/admin_transactions/">
            <i class="mdi mdi-cash menu-icon"></i>
            <span class="menu-title">Transactions</span>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/request/">
            <i class="mdi mdi-file-document menu-icon"></i>
            <span class="menu-title">Fd and RD Requests</span>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/service-requests/">
            <i class="mdi mdi-file-document menu-icon"></i>
            <span class="menu-title">Service Requests</span>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/star-user/">
            <i class="mdi mdi-star menu-icon"></i>

            <span class="menu-title">Star User</span>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">
            <i class="mdi mdi-settings menu-icon"></i>
            <span class="menu-title">Settings</span>
          </a>
        </li>
      </ul>
    </nav>
    <!-- partial -->
    <div class="main-panel">
      <div class="content-wrapper">
        <div class="row">
          <div class="col-md-12 grid-margin">
            <div class="d-flex justify-content-between flex-wrap">
              <div class="me-md-3 me-xl-5">
                <h2>Welcome, Admin</h2>
                <p class="mb-md-0">Admin Dashboard</p>
              </div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-12 grid-margin stretch-card">
            <div class="card">
              <div class="card-body">
                <h4 class="card-title">Overview</h4>
                <div class="d-flex flex-wrap">
                  <div class="d-flex border-md-right flex-grow-1 align-items-center justify-content-center p-3 item">
                    <i class="mdi mdi-account-multiple me-3 icon-lg text-primary"></i>
                    <div class="d-flex flex-column justify-content-around">
                      <small class="mb-1 text-muted">Total Accounts</small>
                      <h5 class="me-2 mb-0">2</h5>
                    </div>
                  </div>
                  <div class="d-flex border-md-right flex-grow-1 align-items-center justify-content-center p-3 item">
                    <i class="mdi mdi-cash me-3 icon-lg text-success"></i>
                    <div class="d-flex flex-column justify-content-around">
                      <small class="mb-1 text-muted">Total Transaction</small>
                      <h5 class="me-2 mb-0">11</h5>
                    </div>
                  </div>
                  <div class="d-flex border-md-right flex-grow-1 align-items-center justify-content-center p-3 item">
                    <i class="mdi mdi-file-document me-3 icon-lg text-warning"></i>
                    <div class="d-flex flex-column justify-content-around">
                      <small class="mb-1 text-muted">Number of Blogs</small>
                      <h5 class="me-2 mb-0">3</h5>
                    </div>
                  </div>
                  <div class="d-flex py-3 flex-grow-1 align-items-center justify-content-center p-3 item">
                    <i class="mdi mdi-settings me-3 icon-lg text-danger"></i>
                    <div class="d-flex flex-column justify-content-around">
                      <small class="mb-1 text-muted">System Status</small>
                      <h5 class="me-2 mb-0">Operational</h5>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        


<div class="container-fluid mt-5">
    <br>
    <h2 class="mb-4 text-center">FD and RD Applications</h2>

    <!-- FD Applications -->
    <div class="card mb-5">
        <div class="card-header bg-grey text-white">
            <h4 class="card-title">FD Applications</h4>
        </div>
        <div class="card-body">
            <div class="table-responsive">
                <table class="table table-striped table-bordered">
                    <thead class="thead-dark">
                        <tr>
                            <th>User</th>
                            <th>Amount</th>
                            <th>Tenure</th>
                            <th>Interest Rate</th>
                            <th>Status</th>
                            <th class="text-center">Actions</th>
                        </tr>
                    </thead>
                    <tbody>
                        
                        <tr>
                            <td>Amir</td>
                            <td>300.00</td>
                            <td>8 months</td>
                            <td>9.00%</td>
                            <td>
                                <span class="badge badge-danger">
                                    Rejected
                                </span>
                            </td>
                            <td class="text-center">
                                <form action="/transactions/approve-fd/2/" method="post" class="d-inline">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-success btn-sm">Approve</button>
                                </form>
                                <form action="/transactions/reject-fd/2/" method="post" class="d-inline">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-warning btn-sm">Reject</button>
                                </form>
                                <form action="/transactions/fd-application/delete/2/" method="post" class="d-inline" onsubmit="return confirm('Are you sure you want to delete this application?');">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-danger btn-sm">Delete</button>
                                </form>
                            </td>
                        </tr>
                        
                        <tr>
                            <td>Amir</td>
                            <td>1300.00</td>
                            <td>8 months</td>
                            <td>12.00%</td>
                            <td>
                                <span class="badge badge-warning">
                                    Pending
                                </span>
                            </td>
                            <td class="text-center">
                                <form action="/transactions/approve-fd/3/" method="post" class="d-inline">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-success btn-sm">Approve</button>
                                </form>
                                <form action="/transactions/reject-fd/3/" method="post" class="d-inline">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-warning btn-sm">Reject</button>
                                </form>
                                <form action="/transactions/fd-application/delete/3/" method="post" class="d-inline" onsubmit="return confirm('Are you sure you want to delete this application?');">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-danger btn-sm">Delete</button>
                                </form>
                            </td>
                        </tr>
                        
                        <tr>
                            <td>Nahida</td>
                            <td>3000.00</td>
                            <td>4 months</td>
                            <td>7.00%</td>
                            <td>
                                <span class="badge badge-success">
                                    Approved
                                </span>
                            </td>
                            <td class="text-center">
                                <form action="/transactions/approve-fd/4/" method="post" class="d-inline">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-success btn-sm">Approve</button>
                                </form>
                                <form action="/transactions/reject-fd/4/" method="post" class="d-inline">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-warning btn-sm">Reject</button>
                                </form>
                                <form action="/transactions/fd-application/delete/4/" method="post" class="d-inline" onsubmit="return confirm('Are you sure you want to delete this application?');">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-danger btn-sm">Delete</button>
                                </form>
                            </td>
                        </tr>
                        
                    </tbody>
                </table>
            </div>
        </div>
    </div>

    <!-- RD Applications -->
    <div class="card mb-5">
        <div class="card-header bg-grey text-white">
            <h4 class="card-title">RD Applications</h4>
        </div>
        <div class="card-body">
            <div class="table-responsive">
                <table class="table table-striped table-bordered">
                    <thead class="thead-dark">
                        <tr>
                            <th>User</th>
                            <th>Amount</th>
                            <th>Monthly Amount</th>
                            <th>Tenure</th>
                            <th>Interest Rate</th>
                            <th>Status</th>
                            <th class="text-center">Actions</th>
                        </tr>
                    </thead>
                    <tbody>
                        
                        <tr>
                            <td>Amir</td>
                            <td>7000.00</td>
                            <td>334.00</td>
                            <td>7 months</td>
                            <td>8.00%</td>
                            <td>
                                <span class="badge badge-danger">
                                    Rejected
                                </span>
                            </td>
                            <td class="text-center">
                                <form action="/transactions/approve-rd/1/" method="post" class="d-inline">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-success btn-sm">Approve</button>
                                </form>
                                <form action="/transactions/reject-rd/1/" method="post" class="d-inline">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-warning btn-sm">Reject</button>
                                </form>
                                <form action="/transactions/rd-application/delete/1/" method="post" class="d-inline" onsubmit="return confirm('Are you sure you want to delete this application?');">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-danger btn-sm">Delete</button>
                                </form>
                            </td>
                        </tr>
                        
                        <tr>
                            <td>Amir</td>
                            <td>1200.00</td>
                            <td>844.00</td>
                            <td>9 months</td>
                            <td>3.00%</td>
                            <td>
                                <span class="badge badge-warning">
                                    Pending
                                </span>
                            </td>
                            <td class="text-center">
                                <form action="/transactions/approve-rd/2/" method="post" class="d-inline">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-success btn-sm">Approve</button>
                                </form>
                                <form action="/transactions/reject-rd/2/" method="post" class="d-inline">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-warning btn-sm">Reject</button>
                                </form>
                                <form action="/transactions/rd-application/delete/2/" method="post" class="d-inline" onsubmit="return confirm('Are you sure you want to delete this application?');">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-danger btn-sm">Delete</button>
                                </form>
                            </td>
                        </tr>
                        
                        <tr>
                            <td>Nahida</td>
                            <td>1770.00</td>
                            <td>989.00</td>
                            <td>8 months</td>
                            <td>3.00%</td>
                            <td>
                                <span class="badge badge-danger">
                                    Rejected
                                </span>
                            </td>
                            <td class="text-center">
                                <form action="/transactions/approve-rd/5/" method="post" class="d-inline">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-success btn-sm">Approve</button>
                                </form>
                                <form action="/transactions/reject-rd/5/" method="post" class="d-inline">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-warning btn-sm">Reject</button>
                                </form>
                                <form action="/transactions/rd-application/delete/5/" method="post" class="d-inline" onsubmit="return confirm('Are you sure you want to delete this application?');">
                                    <input type="hidden" name="csrfmiddlewaretoken" value="KZMuoNwsiLJwxappB8VJn6wPSfvc9iTT5iDCUK8jGwFCG7nM8TBRj5HMOYnFGbqI">
                                    <button type="submit" class="btn btn-danger btn-sm">Delete</button>
                                </form>
                            </td>
                        </tr>
                        
                    </tbody>
                </table>
            </div>
        </div>
    </div>
</div>

      </div>
      <!-- content-wrapper ends -->
      <!-- partial:partials/_footer.html -->
      <footer class="footer">
        <div class="d-sm-flex justify-content-center justify-content-sm-between">
          <span class="text-muted text-center text-sm-left d-block d-sm-inline-block">Copyright © Finovo Bank 2024</span>
        </div>
      </footer>
  <!-- partial -->
  <!-- main-panel ends -->
  </div>
  <!-- main-panel ends -->
  </div>
  <!-- page-body-wrapper ends -->
  </div>
  <!-- container-scroller -->
  
  <!-- plugins:js -->
  <script src="/static/vendors/base/vendor.bundle.base.js"></script>
  <!-- endinject -->
  <!-- Plugin js for this page-->
  <script src="/static/vendors/chart.js/Chart.min.js"></script>
  <script src="/static/vendors/datatables.net/jquery.dataTables.js"></script>
  <script src="/static/vendors/datatables.net-bs4/dataTables.bootstrap4.js"></script>
  <!-- End plugin js for this page-->
  <!-- inject:js -->
  <script src="/static/js_admin/off-canvas.js"></script>
  <script src="/static/js_admin/hoverable-collapse.js"></script>
  <script src="/static/js_admin/template.js"></script>
  <script src="/static/js_admin/script.js"></script>
  <!-- endinject -->
  <!-- Custom js for this page-->
  <script src="/static/js_admin/dashboard.js"></script>
  <script src="/static/js_admin/data-table.js"></script>
  <script src="/static/js_admin/jquery.dataTables.js"></script>
  <script src="/static/js_admin/dataTables.bootstrap4.js"></script>
  <!-- End custom js for this page-->
  
 <script src="/static/js/jquery-3.6.0.min.js"></script>
  <script src="/static/js/bootstrap.bundle.minn.js"></script> 

  


  <script src="/static/js_admin/jquery.cookie.js" type="text/javascript"></script>
  



  
</body>

</html>


