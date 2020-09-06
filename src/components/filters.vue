<template>
  <header>
    <h3 class="page-title">Recommended Products</h3>
    <div class="filter-block">
      <div class="filter-box selected-filter">
        <div class="filter-label">selected Filters:</div>
        <div class="selected-list">
          <span>Continental</span>
        </div>
      </div>
      <div class="filter-box sort-filter">
        <div class="filter-label">selected Filters:</div>
        <select>
          <option>Popularity</option>
          <option>Popularity</option>
        </select>
      </div>
    </div>
  </header>
</template>
<style>
header {
  border-bottom: 1px solid #000;
  margin-bottom: 20px;
  padding-bottom: 10px;
}
.page-title {
  margin-bottom: 22px;
}
.filter-block {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.filter-box {
  display: flex;
  align-items: center;
}
.filter-label {
  font-size: 13px;
  margin-right: 5px;
}
.selected-list {
  border: 1px solid #000;
  display: flex;
  align-items: center;
  height: 30px;
  border-radius: 16px;
  font-size: 13px;
  padding: 5px 12px;
}
.selected-list span {
  display: flex;
  align-items: center;
}
.selected-list span::after {
  content: "x";
  color: #fff;
  background-color: #000;
  width: 15px;
  height: 15px;
  display: block;
  border-radius: 100%;
  text-align: center;
  margin-left: 10px;
}
.sort-filter select {
  background-color: #e2e2e2;
  height: 30px;
  border-radius: 16px;
  padding: 7px;
}
@media (max-width: 580px) {
  .main-wrapper {
    padding: 20px;
  }
}

@media (max-width: 580px) {
  .main-wrapper {
    padding: 15px;
  }
  .page-title {
    font-size: 18px;
    margin-bottom: 5px;
  }
  .filter-block {
    display: none;
  }
}
</style>
