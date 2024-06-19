<template>
<h2>Create an Invoice</h2>
<div class="create-invoice-form">
    <form  method="post">
         
        <fieldset class="form-group">
            <label for="status">Clients</label>
            <select >
                <option>Chris Simba - simbakriss@gmail.com </option>
                <option>Paid</option>
            </select>
          </fieldset>

        <fieldset class="form-group">
            <label for="due_date">Due Date:</label>
            <input type="date" name="due_date" id="due_date">
        </fieldset>

          <fieldset class="form-group">
            <label for="status">Status</label>
            <select >
                <option>Unpaid</option>
                <option>Paid</option>
            </select>
          </fieldset>
    </form>
</div>

</template>
