<script>
  export let nickname = "@alvarezmirand10";
  export let name = "Omar Alvarez";
</script>

<style>
  .Profile-content {
    display: flex;
    align-items: center;
  }
  .Profile-avatar img {
    width: 42px;
    height: 42px;
    border-radius: 50%;
  }
  .Profile-info {
    margin: 0 0 0 0.5em;
  }
  .Profile-info h2 {
    font-size: 14px;
    color: black;
    margin: 0;
    padding: 0;
  }
  .Profile-info span {
    font-size: 12px;
    font-weight: normal;
  }
</style>

<div class="Profile">
  <div class="Profile-container">
    <div class="Profile-avatar">
      <img
        src="https://firebasestorage.googleapis.com/v0/b/dogstagram-97bee.appspot.com/o/Screenshot_20200501_100536.jpg?alt=media&token=517e884d-8a2d-4454-b2ee-31931c4bfc13"
        alt="" />
    </div>
    <div class="Profile-info">
      <h2>{nickname}</h2>
      <span>{name}</span>
    </div>
  </div>
</div>
