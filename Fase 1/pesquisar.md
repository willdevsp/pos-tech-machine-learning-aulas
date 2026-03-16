# Funções para pesquisar

## Numpy
np.ceil 


## matplotlib
fig, axes  = plt.subplots
axes.ravel()
alpha=0.3
axes[idx].text(0.95, 0.95, f'Outliers: {outlier_count}',
                   transform=axes[idx].transAxe, fontsize=9,
                   verticalalignment='top', horizontalalignment='right',
                   bbox=dict(facecolor='white', alpha=0.5, edgecolor='gray'))
    

    for ax in axes[n:1]:
        fig.delaxes(ax)


df[col].mode()



df_encoded = pd.get_dummies(df_clean, columns=categorical_cols, drop_first=True)

