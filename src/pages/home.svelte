<Page name="home">
  <!-- Top Navbar -->
  <Navbar >
    <NavTitle class="nav_title">YourNewPhone</NavTitle>
  </Navbar>

  <BlockTitle>Opzioni</BlockTitle>
  <Menu>
    <MenuItem href="#" text="menu" panelOpen="left"/>
    <MenuItem href="/pro/" text="Cerca Prodotti" />
    <MenuItem href="#" text="Le nostre sedi" />
  </Menu>


  <!-- Toolbar -->
  <!--
  <Toolbar bottom>
  <Link href="ciao.txt">Left Link</Link>
  <Link>Accedi</Link>
  </Toolbar>
  -->
  
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
    Subnavbar, 
    Searchbar, 
    Menu, 
    MenuItem 
  } from 'framework7-svelte';
  

  export let f7route, f7router; // just to remove debug message
</script>