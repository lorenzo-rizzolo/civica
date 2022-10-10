<Page name="home" id="home">
  <!-- Top Navbar -->
  <Navbar>
    <Block class="nav_title">Default_page</Block>
    <NavRight><Link back>Back</Link></NavRight>
  </Navbar>
  
</Page>

<script>
  
  import {
    Accordion, 
    AccordionItem, 
    AccordionContent,
    Icon,
    Page,
    Navbar,
    NavLeft,
    NavTitle,
    NavTitleLarge,
    NavRight,
    Link,
    Toolbar,
    Block,
    BlockTitle,
    List,
    ListItem,
    Row,
    Col,
    Button, 
    theme, 
    TreeviewItem, 
    Treeview,
    Subnavbar, 
    Searchbar, 
    Menu, 
    MenuItem 
  } from 'framework7-svelte';


  export let f7route, f7router; // just to remove debug message
</script>