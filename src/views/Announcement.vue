<template>
  <content-header title="Announcement" />
  <div class="card col-8 offset-2">
    <div class="card-header">
      <h3 class="card-title">Announcement</h3>
    </div>

    <div class="card-body">
      <form>
        <div class="col-xs-4">
          <div class="form-group">
            <label>Title</label>
            <input type="text" class="form-control" placeholder="Title..." />
          </div>
        </div>
        <div class="col-xs-4">
          <div class="form-group">
            <label>Description</label>
            <textarea
              class="form-control"
              rows="5"
              placeholder="Description..."
            ></textarea>
          </div>
          <a href="#" class="btn btn-primary">post</a>
        </div>
      </form>
    </div>
  </div>

  <div class="card col-8 offset-2">
    <div class="card-header">
      <h3 class="card-title">Past Announcement</h3>
    </div>

    <div class="card-body">
      <table class="table table-bordered table-hover">
        <thead>
          <tr>
            <th>Num</th>
            <th>User</th>
            <th>Date</th>
            <th>Title</th>
            <th>Status</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>001</td>
            <td>Admin</td>
            <td>11-7-2023</td>
            <td>This is the title of the announcement.</td>
            <td>
              <button
                type="button"
                class="btn btn-default"
                data-toggle="modal"
                data-target="#modal-lg"
              >
                <i class="far fa-edit"></i>
              </button>
              <button
                type="button"
                class="btn btn-default"
                data-toggle="modal"
                data-target="#modal-sm"
              >
                <i class="far fa-trash-alt"></i>
              </button>
            </td>
          </tr>
          <tr>
            <td>001</td>
            <td>supervisor</td>
            <td>11-7-2023</td>
            <td>This is the title of the announcement.</td>
            <td>
              <button
                type="button"
                class="btn btn-default"
                data-toggle="modal"
                data-target="#modal-lg"
              >
                <i class="far fa-edit"></i>
              </button>
              <button
                type="button"
                class="btn btn-default"
                data-toggle="modal"
                data-target="#modal-sm"
              >
                <i class="far fa-trash-alt"></i>
              </button>
            </td>
          </tr>
          <tr>
            <td>001</td>
            <td>coordinator</td>
            <td>11-7-2023</td>
            <td>This is the title of the announcement.</td>
            <td>
              <button
                type="button"
                class="btn btn-default"
                data-toggle="modal"
                data-target="#modal-lg"
              >
                <i class="far fa-edit"></i>
              </button>
              <button
                type="button"
                class="btn btn-default"
                data-toggle="modal"
                data-target="#modal-sm"
              >
                <i class="far fa-trash-alt"></i>
              </button>
            </td>
          </tr>
          <tr>
            <td>001</td>
            <td>Admin</td>
            <td>11-7-2023</td>
            <td>This is the title of the announcement.</td>
            <td>
              <button
                type="button"
                class="btn btn-default"
                data-toggle="modal"
                data-target="#modal-lg"
              >
                <i class="far fa-edit"></i>
              </button>
              <button
                type="button"
                class="btn btn-default"
                data-toggle="modal"
                data-target="#modal-sm"
              >
                <i class="far fa-trash-alt"></i>
              </button>
            </td>
          </tr>
          <tr>
            <td>001</td>
            <td>Admin</td>
            <td>11-7-2023</td>
            <td>This is the title of the announcement.</td>
            <td>
              <button
                type="button"
                class="btn btn-default"
                data-toggle="modal"
                data-target="#modal-lg"
              >
                <i class="far fa-edit"></i>
              </button>
              <button
                type="button"
                class="btn btn-default"
                data-toggle="modal"
                data-target="#modal-sm"
              >
                <i class="far fa-trash-alt"></i>
              </button>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>

  <!--Hove for Edit and delete button-->
  <div class="modal fade" id="modal-lg">
    <div class="modal-dialog modal-lg">
      <div class="modal-content">
        <div class="modal-header">
          <h4 class="modal-title">Edit Announcement</h4>
          <button
            type="button"
            class="close"
            data-dismiss="modal"
            aria-label="Close"
          >
            <span aria-hidden="true">&times;</span>
          </button>
        </div>
        <div class="modal-body">
          <form>
            <div class="col-xs-4">
              <div class="form-group">
                <label>Title</label>
                <input
                  type="text"
                  class="form-control"
                  placeholder="Title..."
                />
              </div>
            </div>
            <div class="col-xs-4">
              <div class="form-group">
                <label>Description</label>
                <textarea
                  class="form-control"
                  rows="5"
                  placeholder="Description..."
                ></textarea>
              </div>
            </div>
          </form>
        </div>
        <div class="modal-footer justify-content-between">
          <button type="button" class="btn btn-default" data-dismiss="modal">
            Close
          </button>
          <button type="button" class="btn btn-primary">Save changes</button>
        </div>
      </div>
    </div>
  </div>

  <div class="modal fade" id="modal-sm">
    <div class="modal-dialog modal-sm">
      <div class="modal-content">
        <div class="modal-header">
          <h4 class="modal-title">Delete Announcement</h4>
          <button
            type="button"
            class="close"
            data-dismiss="modal"
            aria-label="Close"
          >
            <span aria-hidden="true">&times;</span>
          </button>
        </div>
        <div class="modal-body">
          <p>Delete the Announcement?</p>
        </div>
        <div class="modal-footer justify-content-between">
          <button type="button" class="btn btn-default" data-dismiss="modal">
            Close
          </button>
          <button type="button" class="btn btn-primary">Delete</button>
        </div>
      </div>
    </div>
  </div>
</template>