<script>
    import Post from './Post.svelte';
    
    export let posts;
    </script>
    
    <ul>
    {#each posts as post}
      <li>
        <Post {post} />
      </li>
    {/each}
    </ul>