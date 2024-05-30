<script>
    import "../app.css";
    import { base } from "$app/paths";
</script>
  
<header>
  <nav class='flex w-full lg:w-3/4 m-auto justify-around h-[10vh] items-center bg-black text-white'>
    <a href="{base}/" class="hover:text-white"><i class="fa-solid fa-leaf"></i> GreenLeaf Consulting</a>
    <ul class="flex justify-around w-2/4">
      <li class="hover:text-white">
        <a href="{base}/services">Services</a>
      </li>
      <li class="hover:text-white">
        <a href="{base}/about">About Us</a>
      </li>
      <li class="hover:text-white">
        <a href="{base}/blog">Blog</a>
      </li>
      <li class="hover:text-white">
        <a href="{base}/contact">Contact Us</a>
      </li>
    </ul>
  </nav>
</header>

<slot />

<footer>
  <div class="w-3/4 m-auto flex justify-around">
    <div>
      <h1>GreenLeaf Consultant</h1>
    </div>
    <div class="w-2/4 flex justify-around">
      <h1>Services</h1>
  
      <h1>About Us</h1>
    </div>
  </div>
</footer>
  
  