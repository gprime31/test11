# test11
 A[<a href="https://attacker.com" id="link" target="_blank">hello</a>]
<script>document.getElementById('link').addEventListener('mouseover', function() {
  window.location.href = this.href;  // This triggers the visit of the link
});</script>
