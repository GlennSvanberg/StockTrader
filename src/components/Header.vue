<template>
    <nav class="navbar navbar-default">
        <div class="container-fluid">
            <div class="navbar-header">
                <router-link to="/" class="navbar-brand">Stock Trader</router-link>
            </div>
        
        <div class="navbar-collapse">
            <ul class="nav navbar-nav">
                <router-link to='/portfolio' activeClass="active" tag="li"><a>Portfolio</a></router-link>
                <router-link to='/stocks' activeClass="active" tag="li"><a>Stocks</a></router-link>
            </ul>

            <ul class="nav navbar-nav navbar-right">
                <li><a href="">End Day</a></li>
                <li class="dropdown">
                    <a href="">Save & load</a>
                </li>
            </ul>
        </div>   
        </div>
    </nav>
</template>
