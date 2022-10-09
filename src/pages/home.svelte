<Page name="home">
  <!-- Top Navbar -->
  <Navbar>
    <NavTitle class="nav_title">YourNewPhone</NavTitle>
  </Navbar>

  <Block class="utente"><strong>Utente:</strong></Block>
  <Block id="name_user">Accedi</Block>
  
  <BlockTitle>Opzioni</BlockTitle>
  <Menu>
    <MenuItem class="opt" href="#" text="menu" panelOpen="left"/>
    <MenuItem class="opt" href="/pro/" text="Cerca Prodotti" />
    <MenuItem class="opt" href="#" text="Le nostre sedi"/>
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
    TreeviewItem, 
    Treeview,
    Subnavbar, 
    Searchbar, 
    Menu, 
    MenuItem 
  } from 'framework7-svelte';


  export let f7route, f7router; // just to remove debug message
</script>