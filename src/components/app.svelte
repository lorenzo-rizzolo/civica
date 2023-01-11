<App { ...f7params } >

  <!-- Left panel with cover effect-->
  <Panel right cover dark>
    <View>
      <Page>
        <Navbar class="page_menu" title="Menu"/>
        <Block class="menu">
          <Block  class="link">Mafia</Block><br>
          <Block  class="link">Admin</Block>
        </Block>
      </Page>
    </View>
  </Panel>
  <!-- Your main view, should have "view-main" class -->
  <View main class="safe-areas" url="/" />
</App>
<script>
  function mafia(){
    alert("cioa");
  }
  /*const testAlert = () => alert("alert.");
      const testPrompt = async () => {
      let nome = await prompt("Scrivi il tuo nome: ");
      if(nome){
        //alert(answer);
        document.getElementById('name_user').innerHTML = nome;
      }else{
        alert("Compila tutti e due i campi");
      }
    };*/

  import { onMount } from 'svelte';

  import {
    Button,
    f7,
    f7ready,
    App,
    Icon,
    Panel,
    Views,
    View,
    Popup,
    Page,
    Navbar,
    Toolbar,
    NavRight,
    Link,
    Block,
    BlockTitle,
    LoginScreen,
    LoginScreenTitle,
    List,
    ListItem,
    ListInput,
    ListButton,
    BlockFooter
  } from 'framework7-svelte';


  import routes from '../js/routes';
  import store from '../js/store';

  export let f7route, f7router; // just to remove debug message

  // Framework7 Parameters
  let f7params = {
    name: 'Edcivica', // App name
    theme: 'auto', // Automatic theme detection



    // App store
    store: store,
    // App routes
    routes: routes,
  };
  // Login screen demo data
  let username = '';
  let password = '';

  function alertLoginData() {
    f7.dialog.alert('Username: ' + username + '<br>Password: ' + password, () => {
      f7.loginScreen.close();
    });
  }
  onMount(() => {
    f7ready(() => {


      // Call F7 APIs here
    });
  })
</script>