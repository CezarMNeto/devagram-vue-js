<script lang="ts">
    import { defineComponent } from 'vue'
        
    export default defineComponent({
        data(){
            return {
                resultado: []
            }
        }
    });
</script>
<template>
    <header class="container-header">
        <div class="principal">
            <img src="../assets/imagens/logo-horizontal.svg" alt="logo devagram" />
            <div class="group">
                <div class="pesquisa">
                    <img src="../assets/imagens/busca.svg" alt="pesquisa" layout="fill" class="icon" />
                    <input type="text" placeholder="Pesquisar" />
                </div>
                <!-- Navegação-->
            </div>
        </div>
        <div v-if="resultado.length > 0">
            <!-- Resultado da busca -->
        </div>
    </header>
</template>

<style lang="scss" src="@/assets/styles/inputImagem.scss" />