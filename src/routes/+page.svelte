<script>
	import Image from '../img/1600x900.png?fit=inside&webp&w=480&h=480&meta';
  console.log(Image);
</script>

<p><code>import Image from '../img/1600x900.png?webp&w=480&h=480&meta';</code></p>

<p><img src={Image.src} /></p>

<ul>
  <li><code>Image.src: {Image.src} (should be 16:9)</code></li>
  <li><code>Image.height: {Image.height} (should be 270)</code></li>
  <li><code>Image.src: {Image.width} (should be 480)</code></li>
</ul>