<script>
    import '../app.css'
</script>
<link href="https://fonts.googleapis.com/css?family=Overpass:100,400" rel="stylesheet"/>
<nav>
  <a href="/header">Header</a>
  <a href="/title">Title</a>
  <a href="/images">Images</a>
</nav>
<slot />

<style>
  nav {
    display: flex;
    gap: 1rem;
    padding: 1rem;
    margin-bottom: 5px;
    border-bottom: 1px solid #ff6d43;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);
  }
   a {
    text-decoration: none;
    color: #ff6d43;
    font-weight: 600;
    font-family: 'Overpass';
   }
</style>