<script></script>
<template>
   <div>
    <div class="appbar">
        <h4 class="appbar__title">💰 Xpense Tracker</h4>
    </div>
    <div class="expense">
        <div id="app">
            <form class="form">
                <img class="expense-svg" src="@/assets/images/svg/wallet.svg" alt="">
                <h1 class="expense-heading">
                    Add Transaction.
                </h1>
                <div class="form-input">
                    <label>Expense Name</label>
                    <input type="text" name="expenseName" id="expenseName">
                </div>
                <div class="form-input">
                    <label>Category</label>
                    <select name="expenseCategory" id="expenseCategory">
                        <option value=""></option>
                    </select>
                </div>
                <div class="form-input">
                    <label>Enter Amount</label>
                    <input type="text" name="amount" id="amount">
                </div>
                <button type="submit" id="saveExpenseBtn">Save Expense</button>
            </form>
        </div>
        <div class="footer">
            <p>FarmSpace Media &copy 2021</p>
        </div>
    </div>
   </div> 
</template>